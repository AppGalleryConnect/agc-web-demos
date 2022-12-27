#  Cloud DB JS SDK Demo


## Introduction
This project is a quick start sample developed using Cloud DB JS SDK.

##  Quick Start
- On the [AppGallery Connect](https://developer.huawei.com/consumer/cn/service/josp/agc/index.html#/myProject) page, create a project and add a web application with named `QuickStartDemo`.

- Click **Auth Service** on the navigation bar and enable authentication using an anonymous account.

- Click **Cloud DB** on the navigation bar and enable database service. Then, perform the following operations:

    （1）Create a schema by importing a template file stored in **BookInfo.json** in the `src/components/config/` directory of the project. Alternatively, create a schema named **BookInfo** and ensure that all fields must be the same as those in `src/components/model/BookInfo.js` in the project.

    （2） Create a Cloud DB zone. On the **Cloud DB Zone** tab page, click **Add** to create a Cloud DB zone named **QuickStartDemo**.


- On the Project Setting page, obtain the app configuration information. Save it to the context object in the `src/components/config/agconnect-services.js` file.

- Integrate the Cloud DB SDK.

  Run the following command to install the Cloud DB JavaScript SDK service module in the root directory:
        
  ```
    npm install
  ```

- Compiles and hot-reloads for development.
       
  ```
    npm run start
  ```

## Operate Data

##### 1. Login anonymous.

  ![Login](src/assets/images/login.PNG)

##### 2. Input zone name `QuickStartDemo` and click the `enter` button to open Cloud DB zone.

  ![OpenZone](src/assets/images/openZone.PNG)

##### 3. Insert a record.

  ![Insert](src/assets/images/insert.PNG)

##### 4. Update a record.

  ![Update](src/assets/images/update.PNG)

##### 5. Delete a record.

  ![Delete](src/assets/images/delete.PNG)

##### 6. Query records.

  ![Query](src/assets/images/query.PNG)

