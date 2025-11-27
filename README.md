# Demo Day Project (11-27-2025)

This repository contains the workflow for the Demo Day presentation. Please follow the steps below to set up and run the project in Databricks.

## Setup & Deployment Instructions

1.  **Clone the Repository**
    Clone this repository into your Databricks workspace.

2.  **Initialize Metadata**
    Navigate to `project/bronze/add_metadata` and run the notebook.
    > **Note:** Run this notebook **only once** to initialize the necessary metadata.

3.  **Configure Warehouse ID**
    * Go to the **Compute** tab in Databricks and copy your SQL Warehouse ID.
    * Navigate to the `resources` folder in the repository.
    * Open the `.yml` files and replace the existing `warehouse_id` with your specific ID.

4.  **Deploy the Bundle**
    Open `databricks.yml` and deploy the Databricks Asset Bundles (DABs).

5.  **Run the Job**
    After deployment, a job named `sales_master` will appear in your Workflows. Run this job to execute the pipeline.

## Support

If you encounter any issues during setup or execution, please post in the group chat or contact **t.me/balkibumen** directly.
