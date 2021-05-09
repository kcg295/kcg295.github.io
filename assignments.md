## Assignments

During my time at New York University Tandon School of Engineering I have
developed several assignments for my classes. These are enumerated below.

### Application Security Assignments

##### When a Wreck Reaches the World Wide Web

In this assignment students are given a broken and poorly written website
written in Django. Their job is to do the following:

1. Find four vulnerabilities in the code and patch them.
2. Explain the vulnerabailities they found and how they fixed them.
3. Implement regression testing to ensure the attacks they found no longer work.
4. Trigger that regression testing in a Continuous Integration system.
5. Encrypt sensitive information in the website database.
6. Practice propper key management in their database encryption approach.
7. Sign their git comits.

For more information, this assignment can be found at 
[its repository](https://github.com/kcg295/AppSecAssignment2.1).

##### Deployment Gone Wrong

In this assignment students are given a barely-funcitoning deployment of a web
service. This deployment uses Django and kubernetes, but contains many problems,
including security issues regarding secrets. In this assignment, students must:

1. Find all hard-coded secrets and replace them with Kubernetes secrets.
2. Implement a kubernetes job to apply database structure to the database
microservice.
3. Implement a kubernetes job to pre-load the database with data necessary for
the application to run.
4. Install a monitoring service, Prometheus, to their kubernetes cluster and
configure it to capture data from the deployed web service.
5. Remove vulnerabilities related to improperly configured monitoring.

For more information, this assignment can be found at
[its repository](https://github.com/kcg295/AppSecAssignment3.1).

##### Mobile Mess

In this assignment students are given a barely-functioning Android application
which uses a REST backend (that the students cannot access). In this assignment
students must:

1. Secure Intents by switching implicit Intents to explicit Intents.
2. Upgrade the Android Applicaiton to use HTTPS.
3. Find a vulnerability, through blackbox testing, that allows individuals to
use resources belonging to other accounts.
4. Remove privacy invasive code and minimize permissions of the Android
application.

For more information, this assignment can be found at
[its repository](https://github.com/kcg295/AppSecAssignment4.1).

### Information Security and Privacy Assignments

##### Midterm Assignment

In this assignments students are given a description of an organization's assets
and are required to:

1. Create an attack tree to identify the easiest and most effective attack
against the organization.
2. Step through the Cyber kill-chain to describe the details of how an attack
against the project could occur.
3. Apply knowledge of cryptographic primitives to defend against the attacks 
considered.
4. Compare their applied cryptographic approach to that of an existing solution,
TUF.

For more information, this assignment can be found in
[this pdf](/assets/assignments/Assignment1.pdf).
