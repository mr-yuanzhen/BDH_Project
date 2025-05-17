# CSE 6250: Big Data for Health Informatics Class Project
# 🩺 FarSight: Long-Term Disease Prediction from Nursing Notes (Reproduction)

This project reproduces part of the **FarSight** paper:

> **FarSight: Long-Term Disease Prediction Using Unstructured Clinical Nursing Notes**  
> *Rashmi Gangwar, Ritam Dutt, Harsh Vardhan Pant, Udit Kumar, et al.*

The goal is to predict **ICD-9 diagnostic code groups** using only **unstructured nursing notes** from the MIMIC-III clinical dataset. 
This is a multi-class, multi-label predictive modeling task. This repository replicates the main pipeline using deep learning models — including **NMF on BoW + MLP** and **ClinicalBERT** — for **multi-label disease prediction**.
