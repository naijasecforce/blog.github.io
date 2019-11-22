---
layout: post
title:  "Pyrogenic – The JAR -Based Malware Spreading Across Africa and the Middle East ."
author: Rotimi
categories: [ Malware, Hacking ]
tags: [rotimi, naijasecforce, malware]
image: ../assets/malware-featured.jpg
description: "Malware discovered."
featured: true
hidden: true
rating: 4.5
---

## Overview
Red Teaming has rapidly transitioned from Living off the Land (LotL) to Bringing Your Own Land (BYOL). 
It is now possible to execute .NET assemblies entirely within memory. By developing custom C#-based assemblies, 
attackers no longer need to rely on the tools present on the target system; they can instead write and deliver 
their own tools, a technique called Bring Your Own Land (BYOL).  This has led to transitions from PowerShell tools 
(e.g. PowerShell Empire) to frameworks targeted for .NET assemblies. {shamelessly copied from 
https://www.fireeye.com/blog/threat-research/2018/06/bring-your-own-land-novel-red-teaming-technique.html}

## About Covenant
Covenant is a .NET command and control framework that aims to highlight the attack surface of .NET, make the use 
of offensive .NET tradecraft easier, and serve as a collaborative command and control platform for red teamers. 
Covenant is an ASP.NET Core, cross-platform application that includes a web-based interface that allows for 
multi-user collaboration.

![](../assets/images/1.png)
_Figure 1: Covenant dashboard showing Grunts (active PWNED systems), listeners and executed tasks_


## About the Author:
Chinedu Onwukie is an experienced red teaming professional based in Canada. He has multiple years of management 
and technical security experience cutting across consulting, banking, technology and insurance industry.
