# C# - List Queue Members Tutorial

This project serves as a guide to help you build an application with FreeClimb. View this tutorial on [FreeClimb.com](https://docs.freeclimb.com/docs/list-queue-members#section-c). Specifically, the project will:

- List the callers that are members of the specified queue

## Setting up your new app within your FreeClimb account

To get started using a FreeClimb account, follow the instructions [here](https://docs.freeclimb.com/docs/getting-started-with-freeclimb).

## Setting up the Tutorial

1. Install the nuget packages necessary using command:

   ```bash
   $ dotnet add package freeclimb-cs-sdk --version 1.0.0.2
   ```

2. Configure environment variable

   | ENV VARIABLE            | DESCRIPTION                                                                                                                                                                             |
   | ----------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
   | ACCOUNT_ID              | Account ID which can be found under [API Keys](https://www.freeclimb.com/dashboard/portal/account/authentication) in Dashboard                                                         |
   | AUTH_TOKEN              | Authentication Token which can be found under [API Keys](https://www.freeclimb.com/dashboard/portal/account/authentication) in Dashboard                                               |

3. Provide a value for the variable `queueId` which is the id of the queue you wish to list the members of. To learn more about queue go [here](https://docs.freeclimb.com/reference/call-queues).

## Runnning the Tutorial

1. Run the application using command:

   ```bash
   $ dotnet run
   ```
