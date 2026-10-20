---
title: "On-device Vision Anomaly Detection"
date: 2026-10-20
draft: false
description: "Lightweight computer-vision model that detects manufacturing defects in real time on edge hardware, without sending images to the cloud."
domains: ["Artificial Intelligence"]
institutions: ["Kwangwoon University"]
trl: "TRL 5"
ip_status: "1 KR patent granted, PCT pending (sample)"
collaboration: ["Licensing", "Joint Development", "PoC"]
researcher: "Research team (sample)"
validation: "Validated on an internal defect dataset; factory-line pilot pending"
is_sample: true
categories: ["technology"]
---

> **Sample entry** — placeholder content for the showroom prototype.

## Problem

Visual inspection on production lines is still largely manual or relies on cloud-based vision systems that add latency, bandwidth cost, and data-privacy concerns. Many manufacturers cannot send product images off-site.

## Solution & USP

A compact anomaly-detection model (< 10 MB) that runs on low-power edge hardware and flags defects in real time directly on the line. It learns from a small set of "normal" samples, so no large labeled defect dataset is required. All inference stays on-device.

## Applications & Use Cases

- Surface-defect detection in electronics and metal parts
- Packaging and print-quality inspection
- In-line quality control where cloud connectivity is restricted

## Validation Status

Trained and evaluated on an internal dataset with high precision/recall on seeded defects. Next step is a supervised pilot on a live production line with a partner.

## Collaboration

Open to licensing, joint development to adapt the model to a partner's product line, and a scoped PoC on the partner's defect data.
