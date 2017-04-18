# LendFast Origination with DEMO profile

### Info:

This template deploys a collection of containers based upon the technologies below
* **LendFast Origination** - The core system of LendFast Origination system
* **Solr** - Search Indexing system
* **CDS** - Credit Decision System
* **UASAdmin** - System to manage User, Workgroup and Roles
* **Fakehost** - Mock of host system
* **Reporting Dashboard** - Reporting Dashboard system

## Usage
* After creation of this stack, you will need to create a load balancer to allow incoming traffic to the stack.

## Load Balancer Rule
* Reporting Dashboard
	- Path: /reporting-dashboard-service
	- Target: reportingdashboard
