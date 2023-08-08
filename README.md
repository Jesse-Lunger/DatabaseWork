# Art Broker

This is part of a project that I contributed to. It is a server that uses uses hashed image
pairs uploaded into an SQL database to prove ownership of an image. It allows for images
to be traded through a secure hash methods. Every hash is marked with a date of upload that proves
that at what time the photo was uploaded and the state it was in. This helps to reduced data contraints
on the database while also acting as a sterilization process to protect against SQL injections.

The code to set up the database was not included, I generated it through mysql workbench diagram and then latter
modified it to fit my purposes.
