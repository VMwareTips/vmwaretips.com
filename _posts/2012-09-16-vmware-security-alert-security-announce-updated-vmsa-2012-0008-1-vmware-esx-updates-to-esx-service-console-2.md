---
id: 1717
title: 'VMware Security Alert &#8211; [Security-announce] UPDATED VMSA-2012-0008.1 VMware ESX updates to ESX Service Console'
date: 2012-09-16T21:15:19+00:00
author: Rick Scherer
layout: post
guid: http://vmwaretips.com/wp/?p=1717
permalink: /2012/09/16/vmware-security-alert-security-announce-updated-vmsa-2012-0008-1-vmware-esx-updates-to-esx-service-console-2/
redirect_from: /wp/2012/09/16/vmware-security-alert-security-announce-updated-vmsa-2012-0008-1-vmware-esx-updates-to-esx-service-console-2/
ratings_users:
  - "0"
ratings_score:
  - "0"
ratings_average:
  - "0"
views:
  - "988"
categories:
  - Alert
tags:
  - alert
  - Bug
  - patch
  - support
  - VMware
---
In our effort to provide our viewers with up to the minute information on VMware related news and topics, we&#8217;re posting the following Security Alert direct from the VMware Security Alert distribution.



> &#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;
                     
> VMware Security Advisory
> 
> Advisory ID: VMSA-2012-0008.1
  
> Synopsis: VMware ESX updates to ESX Service Console
  
> Issue date: 2012-04-26
  
> Updated on: 2012-09-13
  
> CVE numbers: CVE-2010-4008, CVE-2011-0216, CVE-2011-1944, CVE-2011-2834,
               
> CVE-2011-3191, CVE-2011-4348, CVE-2012-0028, CVE-2011-3905,
               
> CVE-2011-3919
   
> &#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8211;
  
> 1. Summary
> 
> VMware ESX updates to ESX Service Console.
> 
> 2. Relevant releases
> 
> ESX 4.1 without patches ESX410-201204401-SG,ESX410-201204402-SG
> 
> 3. Problem Description
> 
> a. ESX third party update for Service Console kernel
> 
> The ESX Service Console Operating System (COS) kernel is updated
      
> which addresses several security issues in the COS kernel.
> 
> The Common Vulnerabilities and Exposures project (cve.mitre.org) has
      
> assigned the names CVE-2011-3191, CVE-2011-4348 and CVE-2012-0028 to
      
> these issues.
> 
> Column 4 of the following table lists the action required to
      
> remediate the vulnerability in each release, if a solution is
      
> available.
> 
> VMware Product Running Replace with/
      
> Product Version on Apply Patch
      
> ============= ======== ======= =================
      
> vCenter any Windows not affected
> 
> hosted * any any not affected
> 
> ESXi any ESXi not affected
> 
> ESX 4.1 ESX ESX410-201204401-SG
      
> ESX 4.0 ESX see VMSA-2012-0013 **
      
> ESX 3.5 ESX not applicable
> 
> * hosted products are VMware Workstation, Player, ACE, Fusion.
> 
> ** Two of the three issues, CVE-2011-3191 and CVE-2011-4348, have
       
> already been addressed on ESX 4.0 in an earlier kernel patch. See
       
> VMSA-2012-0006 for details.
       
> CVE-2012-0028 is addressed by a later kernel patch, see
       
> VMSA-2012-0013.
> 
> b. Updated ESX Service Console package libxml2
> 
> The ESX Console Operating System (COS) libxml2 rpms are updated to
      
> the following versions libxml2-2.6.26-2.1.12.el5_7.2 and
      
> libxml2-python-2.6.26-2.1.12.el5_7.2 which addresses several
      
> security issues.
> 
> The Common Vulnerabilities and Exposures project (cve.mitre.org) has
      
> assigned the names CVE-2010-4008, CVE-2011-0216, CVE-2011-1944,
      
> CVE-2011-2834, CVE-2011-3905, CVE-2011-3919 to these issues.
> 
> Column 4 of the following table lists the action required to
      
> remediate the vulnerability in each release, if a solution is
      
> available.
> 
> VMware Product Running Replace with/
      
> Product Version on Apply Patch
      
> ============= ======== ======= =================
      
> vCenter any Windows not affected
> 
> hosted * any any not affected
> 
> ESXi any ESXi not affected
> 
> ESX 4.1 ESX ESX410-201204402-SG
      
> ESX 4.0 ESX see VMSA-2012-0013
      
> ESX 3.5 ESX not applicable
> 
> * hosted products are VMware Workstation, Player, ACE, Fusion.
> 
> 4. Solution
> 
> Please review the patch/release notes for your product and version
     
> and verify the checksum of your downloaded file.
> 
> ESX 4.1
     
> &#8212;&#8212;-
     
> ESX410-201204001
     
> md5sum: 7994635547b375b51422b1a166c6e214
     
> sha1sum: 9d5f3c9cbc53a9e03524b9bf0935c71f3dadf620
     
> http://kb.vmware.com/kb/2013057
> 
> ESX410-201204001 contains ESX410-201204401-SG and
     
> ESX410-201204402-SG
> 
> 5. References
> 
> http://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2010-4008
     
> http://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2011-0216
     
> http://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2011-1944
     
> http://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2011-2834
     
> http://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2011-3191
     
> http://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2011-4348
     
> http://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2012-0028
     
> http://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2011-3905
     
> http://cve.mitre.org/cgi-bin/cvename.cgi?name=CVE-2011-3919
> 
> &#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8211;
> 
> 6. Change log
> 
> 2012-04-26 VMSA-2012-0008
     
> Initial security advisory in conjunction with the release of
     
> patches for ESX 4.1 on 2012-04-26.
> 
> 2012-09-12 VMSA-2012-0008.1
     
> Updated security advisory in conjunction with the release of
     
> vSphere 4.0 U4a on 2012-09-12 and ESX 4.0 patches on 2012-09-13.
> 
> &#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8212;&#8211;
> 
> 7. Contact
> 
> E-mail list for product security notifications and announcements:
  
> http://lists.vmware.com/cgi-bin/mailman/listinfo/security-announce
> 
> This Security Advisory is posted to the following lists:
> 
> * security-announce at lists.vmware.com
    
> * bugtraq at securityfocus.com
    
> * full-disclosure at lists.grok.org.uk
> 
> E-mail: security at vmware.com
  
> PGP key at: http://kb.vmware.com/kb/1055
> 
> VMware Security Advisories
  
> http://www.vmware.com/security/advisories
> 
> VMware security response policy
  
> http://www.vmware.com/support/policies/security_response.html
> 
> General support life cycle policy
  
> http://www.vmware.com/support/policies/eos.html
> 
> VMware Infrastructure support life cycle policy
  
> http://www.vmware.com/support/policies/eos_vi.html
> 
> Copyright 2012 VMware Inc. All rights reserved.
  
> \___\___\___\___\___\___\___\___\___\___\___\___\___\___\_____
  
> Security-announce mailing list
  
> Security-announce@lists.vmware.com
  
> http://lists.vmware.com/mailman/listinfo/security-announce