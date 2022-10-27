# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...


Models & Tables
Doctors

first_name
last_name
zip_code
Specialties

specialty
DoctorSpecialties

A doctor would have several specialties (DEAL_WITH_IT), and a specialty could involve several doctors.
Patients

first_name
last_name
Appointments

date
An appointment can only have one doctor, but a doctor can have several appointments.

An appointment can only have one patient, but a patient can have several appointments.

A doctor can have several patients, through appointments, and vice versa.

Cities
name
A city can have several doctors, patients, and appointments.