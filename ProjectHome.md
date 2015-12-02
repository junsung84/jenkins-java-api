# Introduction #
A Java API to connect to jenkins.

# How to use it #
```
JenkinsClient client = new JenkinsClient("http://localhost:8080/jenkins");
client.authenticate("user", "pass");

List<JobStatus> status = client.readJobStatus()
```

More functions are available !!!