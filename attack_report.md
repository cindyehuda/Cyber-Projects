# 🛡️ Web Attack Analysis Report

Date: 23/11/2025

## Overview

This document provides a full analysis of a web-server compromise
performed via file upload vulnerability exploitation.

## Environment Details

-   Attacker IP: 10.0.0.50
-   Web Server IP: 10.0.0.20
-   Upload Endpoint: http://10.0.0.20/upload.php
-   Malicious File: reverse_proxy.php

## Reconnaissance

    nmap -sV -p 1-1000 10.0.0.20
    nmap -sV -p 80,443 10.0.0.20

## Evidence

    10.0.0.50 - - [23/Nov/2025:14:01:09 +0200] "GET / HTTP/1.1"
