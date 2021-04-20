# sca_reminder_app_flutter
![ezgif com-gif-maker](https://user-images.githubusercontent.com/32166619/115328615-c2c13c00-a188-11eb-91fb-6b9037f97211.png)

A new Flutter application.

## Folder Structure

### src

Since the main.dart file is out of src and we will only write the application codes in the src package. When main.dart will executex as root file, it would be redirected to the src\app.dart file which will contain all the MaterialApp/CupertinoApp components of the project.

business_logic: All the logical parts of the project will be located in this package.

    blocs: If you are following the BLoC pattern then you can keep your blocs here.
    models: Models/Pojo classes.
    services: There are three types of services - api_services, database_services, shared_prefs_services. You will put your specific types of codes in the specific type of service packages.
    utils: This package contains all the constants files.

### views

We will put our User Interface codes insides our views package.

    ui: All the User Interface code files.
    utils: This package contains the reusable widgets files and the constants value files.
