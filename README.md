# datatdog_support_koerber
Hi team, please see file *jboss_indented.yaml* in this repository, please copy it to the /etc/datadog-agent/conf.d/jboss_wildfly.d directory on your host ffmgrdfwmsdbapp01intarc. 

You will need to update the password information in the file.


Once the file is in the correct directory, please restart your agent with the command sudo systemctl restart datadog-agent, from there navigate to the Datadog UI and see if you're able to receive metrics from your jboss instance
