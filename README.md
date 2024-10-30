# zoho-to-xero-invoice
Zoho Deluge Script. From Zoho CRM work order to Xero invoice automated script using Zoho Workflow rules and function from Developer hub

# You need a custom Xero connection on Zoho CRM
Here is the link to create a custom Xero connection [Custom Xero Connection](https://help.zoho.com/portal/en/kb/fsm/custom-integrations/xero/articles/xero-integration#Create_a_connection_for_Xero)

# Add workflow rule in Zoho CRM
You need to create a workflow rule under the Setting > Automation > Workflow Rule
select Work Order Module and add meaningful name to the rule with meaningful name

# Attach this Deluge script to your workflow rule with the Instant action FUNCTION
copy and paste this script to your newly created function
And change the value of ```xeroConnection``` variable inside the script

# Thanks
