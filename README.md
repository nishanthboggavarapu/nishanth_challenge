# nishanth_challenge
Coding test explanation:

I have created an ansible playbook to Install and configure Apache web serve (using apt and service modules) and deploy the sample application using copy and apt module.

I have then generated SSL certificate command module to trigger openssl command and using command and copy module I am configuring apache. Then I am using handler to reload apache2

Then I am using test_url module to run and test automated test scripts and then using URI module I am testing the status_code with the expected_status_code of 200.
