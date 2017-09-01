# CreateSPOnlineSites
PowerShell to Create SharePoint Online Sub Sites, Libraries/Lists and Activate Features


To execute the PowerShell script we will have to update the below variables located at the end of the script.

$siteCollectionUrl = '<Site Collection Url>'
  
$username = '< Admin Username>'

$password = '< Admin Password>' 

<Sites>
    <Site Name="Human Resources" Url="Human-Resources" Template="STS#0" />
    <Site Name="Sales" Url="Sales" Template="STS#0">
        <Site Name="Client 1" Url="Client-1" Template="STS#0" />
        <Site Name="Client 2" Url="Client-2" Template="STS#0" />
        <Site Name="Client 3" Url="Client-3" Template="STS#0" />
    </Site>
    <Site Name="Projects" Url="Projects" Template="PROJECTSITE#0">
        <Site Name="Project 1" Url="Project-1" Template="PROJECTSITE#0">
            <Site Name="Team 1" Url="Team-1" Template="PROJECTSITE#0" />
            <Site Name="Team 2" Url="Team-2" Template="PROJECTSITE#0" />
            <Site Name="Team 3" Url="Team-3" Template="PROJECTSITE#0" />
        </Site>
        <Site Name="Project 2" Url="Project-2" Template="PROJECTSITE#0">
            <Site Name="Team 1" Url="Team-1" Template="PROJECTSITE#0" />
            <Site Name="Team 2" Url="Team-2" Template="PROJECTSITE#0" />
            <Site Name="Team 3" Url="Team-3" Template="PROJECTSITE#0" />
        </Site>
        <Site Name="Project 3" Url="Project-3" Template="PROJECTSITE#0">
            <Site Name="Team 1" Url="Team-1" Template="PROJECTSITE#0" />
            <Site Name="Team 2" Url="Team-2" Template="PROJECTSITE#0" />
            <Site Name="Team 3" Url="Team-3" Template="PROJECTSITE#0" />
        </Site>
    </Site>
    <Site Name="Marketing" Url="Marketing" Template="STS#0" />
    <Site Name="Accounting" Url="Accounting" Template="STS#0" />
    <Site Name="News" Url="News" Template="BLANKINTERNET#0" />
    <Site Name="Executive Blog" Url="Blog" Template="BLOG#0">
        <Site Name="CEO's Blog" Url="CEO" Template="BLOG#0" />
        <Site Name="Mike's Wisdom" Url="Mike" Template="BLOG#0" />
        <Site Name="Words from Shen" Url="Shen" Template="BLOG#0" />
    </Site>
    <Site Name="Search" Url="Search" Template="SRCHCEN#0" />
    <Site Name="Reports" Url="Reports" Template="BICenterSite#0" />
    <Site Name="OrgWiki" Url="OrgWiki" Template="WIKI#0" />
    <Site Name="Document Center" Url="DocCenter" Template="BDR#0" />
    <Site Name="Organization Policies" Url="OrgPolicies" Template="POLICYCTR#0"></Site>
</Sites> 
