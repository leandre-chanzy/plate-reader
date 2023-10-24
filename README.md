<div align="center">
 <h1>Plate Reader</h1>
 <p>Cheap plate reader link to MySQL (mariadb). Can run on raspberry with a debian with ALPRD.</p>
</div>

# Introduction

This GitHub repository contains a Python script for managing a parking system. The script allows users to enter vehicle information when a vehicle enters the parking area and records the time of entry and exit. It also provides options for querying the database to retrieve information about the vehicles parked.

# Script Overview

The Python script `script.py` provides the following functionality:

- Database Configuration: The script allows you to configure the database connection by providing the host, database name, user, and password.
- Entry and Exit Management: It supports the entry and exit of vehicles by capturing the license plate and timestamp of each event.
- Database Queries: The script allows you to perform various queries on the database, including:
- - Retrieving all parking entries
- - Retrieving entries based on a specified date
- - Retrieving entries based on a specific ID
- - Retrieving entries based on a license plate
- VIP Access: VIP access is mentioned in the script but currently commented out. You can customize this part of the script to implement VIP access rules.

# Script Notes

The script is designed for managing a parking system and is currently set up to use a MySQL database.
You may customize and extend the script to suit your specific requirements, such as integrating with a different database or adding additional features.
The script includes commented-out code related to VIP access, which can be modified and uncommented to implement VIP access control.
