---
id: install
sidebar_label: BI Hub Agents Installation
title: BI Hub Agents Installation
---

import useBaseUrl from "@docusaurus/useBaseUrl";
import Link from '@docusaurus/Link';
import Zoom from "react-medium-image-zoom";
import "react-medium-image-zoom/dist/styles.css";

This section is applicable and same for all the agents which are being released and supported by BI Hub.
Download the required agents from product downloads page.

Follow the steps below to install and configure the BI Hub Agents.

1. Double Click on the `<desired agent name>Agent-X.X.X-windows-installer.exe` file to start the installation process.
1. Click Next in the startup page.
1. Read through the license terms and conditions. To proceed further accept the license terms and click next to continue.
1. In the Directory Selection screen, choose the directory to install BI Hub Server.  The default directory is `C:\Program Files\Visual BI Solutions\BI Hub\<installing agent name>Agent`.
1. On clicking next you will be shown Agent port details screen. Accept the default port or else provide your own port details. Make sure that the given port is free and not used by other applications. Kindly make note of these ports, since you will need these port details while configuring the agent which can be found at <Link to={useBaseUrl('docs/admin-guide/admin-functions/integrate-bihub-platform-msad/add-new-agent')}>BI Hub Administration Guide,  Add New Agent</Link>.
1. The next screen provides details of installation. Clicking next button will start to install the BI Hub Agent.
1. Kindly wait for the installation to finish. After successful installation, the final screen provides options to Open Readme file

:::success
You have successfully installed BI Hub Agent in your Server.
:::

Repeat all the above steps to install other required agents. Proceed to next section for configuring the agent, after finished installing all the required agents.
