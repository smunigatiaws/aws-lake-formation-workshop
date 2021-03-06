+++
title = "What is Lake Formation?"
chapter = true
weight = 100
autoNav = true
+++

<center><h3>What Is AWS Lake Formation?</h3></center>

<div style="text-align: justify">

    Lake Formation is a managed service that makes it easy for you to set up, secure, and manage your data lakes. With
    Lake Formation, you can prepare your data for analysis and machine learning. Lake Formation helps you discover your
    data sources and catalog, cleanse, and transform the data. You can then use Lake Formation to secure and ingest the
    data into an Amazon Simple Storage Service (Amazon S3) data lake.

    <br /><br />
    Moving your data into a data lake can provide better flexibility, cost savings, and scalability. However, manually
    setting up and managing data lakes can be a complex and time-consuming process. Lake Formation provides the
    following capabilities, either directly or through other AWS services, to reduce the time to deploy data lakes from
    many months to a few days or weeks:<br />
    <ul>
        <li>Ingest and organize data.</li>
        <li>Cleanse data.</li>
        <li>Catalog and index data.</li>
        <li>Analyze data.</li>
        <li>Secure data at the database and table level.</li>
        <li>Grant data access to users from a central location.</li>
        <li>Orchestrate data flows.</li>
    </ul>

    Lake Formation uses the following services:
    <ul>
        <li>AWS Glue to orchestrate jobs with triggers to transform data using the AWS Glue transforms.</li>
        <li>AWS Identity and Access Management (IAM) to secure data using Lake Formation permissions to grant and revoke
            access.
        </li>
        <li>The Data Catalog as the central metadata repository across several services.</li>
        <li>Amazon Athena to query data.</li>
        <li>Amazon SageMaker to analyze data.</li>
        <li>AWS Glue machine learning transforms to cleanse data.</li>
    </ul>

</div>
