# DS-Olympic

Competition Description

The DGCS (french acronym for Direction Générale de la Cohésion des Territoires, in english General Directorate for Territorial Cohesion) is linked to the French ministry of territorial cohesion. Its mission is to design, direct and evaluate public policies regarding solidarity, social development and equality promotion so as to foster social cohesion and support people self-reliance.

Recently, the DGCS renovated and standardized the information system of the centers responsible for emergency housing distribution. The data of this challenge comes from this renovation project.

Families in emergency situations live on the streets or do not have a home.

We can compare this problem to the accommodation for refugees, which must be dispatched in care center.

The goal is to predict the number of nights an emergency service can provide to an individual or a group (couple, family, …).

The data contains about 480k samples (with data related to requests, groups and individuals). The number of nights is only known for a subset of requests (the learning base). Your objective is to predict the number of nights for the requests of the test dataset.

The target represents a categorized number of nights that the person or group will stay in an emergency structure:

    - 0: the person or group won’t be granted a solution or has refused it
    - 1: 1 or 2 nights
    - 2: between 3 nights (included) and 1 month
    - 3: more than 1 month
