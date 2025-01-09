# webinar-app-migration

## Migration applications to Openshift
<pre>
- Lift and Shift
  - take an application that today runs outside Openshift, deploy them in openshift as - it with minimal changes
  - this approach doesn't work for all applications
  - may be not the ideal approach, but it still works for some applications
- let's say we wanted to deploy Java application that interacts with db
  - Approach 1 
    - create a container image that has both Java application and db server
  - Approach 2 
    - create one container image that just has the java application - deploy java app separately
    - create another container that deploys the db server

</pre>
