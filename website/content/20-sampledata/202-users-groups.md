+++
title = "Users & Groups"
chapter = true
weight = 202
+++

<div style="text-align: justify">
    <center><h2>Test Users & Groups</h2></center>
    To demonstrate different Lake Formation security capabilities, we will use few test users & group, where each of the
    user has different level of access to the data lake. The CloudFormation template that creates TPC data, also creates
    these sets of users and groups in an Active Directory.

    <ul>
        <li><b>lf-developer</b> can only see <b>web_page</b> & <b>web_sales</b> tables.</li>
        <li><b>lf-campaign_manager</b> can see everything except <b>web_page</b> table.</li>
        <li><b>lf-business_analyst</b> can see everything except <b>web_page</b>, <b>web_sales</b> and cannot check customer personal information, for example: email address, address, date of birth, etc.</li>
        <li><b>lf-admin</b> has access to all Lake Formation components and can make any changes in Lake Formation.</li>
    </ul>
</div>
