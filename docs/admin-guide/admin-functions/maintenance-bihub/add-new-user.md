---
id: add-new-user
title: Adding a new user to BI Hub
sidebar_label: Adding a new user to BI Hub
---

import useBaseUrl from "@docusaurus/useBaseUrl";
import Link from '@docusaurus/Link';
import Zoom from "react-medium-image-zoom";
import "react-medium-image-zoom/dist/styles.css";

This section can be used by administrator to add users manually from Microsoft AD to BI Hub. Click on User Manager from the application pane.

1. Click on Add User on the right top as shown below.

  <div style={{textAlign: 'center'}}>
    <Zoom>
      <img alt="Add User option" src={useBaseUrl('doc-images/admin-guide/admin-functions/maintenance-bihub/adduseroption.jpg')}/>
    </Zoom>
  </div>

  *Add User option*

1. Type in the full name, and choose Native to add a user who will be authenticated by BI Hub (because the user is currently authenticated by BI platforms and not AD) OR choose Windows AD to add a user who will be authenticated by Windows AD.

  <div style={{textAlign: 'center'}}>
    <Zoom>
      <img alt="Add User" src={useBaseUrl('doc-images/admin-guide/admin-functions/maintenance-bihub/adduser.jpg')}/>
    </Zoom>
  </div>

1. Click continue.
1. Select the agent to be added for the user and the corresponding username. Click on Add to add more agents.
1. Click on Submit.
1. The added user will be reflected in the User Manager Page.
1. In order to synchronize reports for this user, one of the following actions can be performed
  
  - Wait till the next scheduled synchronization activity happens.
  - Follow steps in Section <Link to={useBaseUrl('docs/admin-guide/admin-functions/integrate-bihub-platform-msad/synch-reports-users')}>Synchronize Reports of Users</Link> to Sync Reports with a single click
  - Manually add reports to the user using User Manager as explained in section <Link to={useBaseUrl('docs/admin-guide/admin-functions/maintenance-bihub/add-reports-existing-user')}>Add Reports to an existing user</Link>.
