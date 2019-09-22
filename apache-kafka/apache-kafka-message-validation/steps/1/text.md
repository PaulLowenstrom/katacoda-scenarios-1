In this step, we will setup VScode editor and clone respository.

Click **IDE Editor** tab to open Visual Studio and click _Terminal_ > _New Terminal_ to open the VSCode integrated terminal which wil be used to run commands.

Next, clone the following repository by copying & executing following command in the vscode terminal.
`git clone https://github.com/athertahir/kafka.git`{{copy}}

#### Permissions
Now, move in the directory which contains scripts to install kafka, copy and execute the command. We also need to change permission to execute the script using **chmod**.
`cd HLFADV/setup/kafka && chmod 755 *.sh`{{copy}}

**Note:**
The supplied commands in the next steps MUST be run from your setup/kafka sub-directory of the **HLFADV** repository clone.

Let's present our case study. We need to model the systems of Monedero, a fictional company whose core business is cryptocurrency exchange. Monedero wants to base its IT infrastructure on an enterprise service bus (ESB) built with Apache Kafka. The Monedero IT department wants to unify the service backbone across the organization. Monedero also has worldwide, web-based, and mobile-app-based clients, so a real-time response is fundamental.

In this scenario, we will cover the following topics:

- Modeling the messages in JSON format
- Setting up a Kafka project with Gradle
- Reading from Kafka with a Java client
- Writing to Kafka with a Java client
- Running a processing engine pipeline
- Coding a Validator in Java
- Running the validation