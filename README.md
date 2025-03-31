UiPath Social Automation Snippets
This repository contains several UiPath workflows designed to automate common social media tasks, including extracting user information, following/unfollowing users, and verifying who is being followed by a specific profile. Each folder in this repository corresponds to a distinct workflow or feature set.

Overview

These UiPath workflows help automate social interactions on various platforms by:

1. Extracting information about other users.

2. Following or unfollowing specific accounts.

3. Verifying who is currently being followed by a particular user profile.

4. They are intended to reduce manual effort and streamline routine tasks such as user engagement and data collection.

Features

1. User Extraction

Retrieves profile details and relevant user information.

Useful for data collection or reporting.

2. Follow/Unfollow Automation

Automates the process of following targeted users or unfollowing inactive profiles.

Ideal for maintaining a curated follower list.

3. Follow Verification

Checks which users are currently followed by a given account.

Helps maintain accurate records of follow relationships.

Prerequisites

1. UiPath Studio

Make sure you have UiPath Studio installed (preferably the latest version) or UiPath StudioX if the workflows are compatible.


2. Web Browser

Most scripts assume usage of Chrome or Firefox. Ensure you have the appropriate UiPath browser extensions installed.

3. Credentials & Access

If these scripts interact with private user accounts, you’ll need valid login credentials.

Make sure to store sensitive information securely (e.g., UiPath Orchestrator Assets, Windows Credential Manager, or an encrypted file).

4. Dependencies

Check each workflow’s project.json file to see which packages it requires (e.g., UiPath.WebAPI.Activities, UiPath.Excel.Activities, etc.).

