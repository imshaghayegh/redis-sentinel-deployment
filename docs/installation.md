# Redis Sentinel Installation Guide

## Overview

This document describes the installation and configuration procedure
for Redis and Redis Sentinel using the official Redis binary package.

# Prerequisites

Minimum requirements:

- Linux server
- CPU: 2 Core
- RAM: 4 GB
- Network connectivity between Redis nodes

Required ports:

| Service | Port |
| Redis | 6379 |
| Sentinel | 26379 |

# Installation

## Download Redis Package

Download Redis binary package:

```bash
wget https://download.redis.io/releases/redis-8.0.5.orig.tar.gz
