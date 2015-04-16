Ghost on OpenShift
=========================
Ghost is an awesome blogging platform. Looks great out of the box. Just try it yourself.

More information can be found on the official Ghost website at http://ghost.org

Ghost Version Installed by this repo: 0.6.0

Running on OpenShift
--------------------

Create an account at http://openshift.redhat.com/

Install `rhc` client tool as instructed at https://developers.openshift.com/en/managing-client-tools.html

Setup client tool if you haven't done so:  
`rhc setup`

Create app:   
`rhc app create myblog nodejs-0.10 postgresql-9.2 --from-code https://github.com/aatishnn/openshift-ghost-quickstart#master`

That's it, you can now fully enjoy Ghost. Access `/admin` on your app to configure Ghost for the first time.

Notes
------
Scripts and some code copied and modified from https://github.com/openshift-quickstart/openshift-ghost-quickstart

@aatishnn
