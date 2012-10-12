=====================
django_localflavor_kw
=====================

Country-specific Django helpers for Kuwait.

What's in the Kuwait localflavor?
=================================

* forms.KWCivilIDNumberField: A form field that validates input as a Kuwaiti
  Civil ID number. A valid Civil ID number must obey the following rules:

  * The number consist of 12 digits.
  * The birthdate of the person is a valid date.
  * The calculated checksum equals to the last digit of the Civil ID.

See the source code for full details.

About localflavors
==================

Django's "localflavor" packages offer additional functionality for particular
countries or cultures.

For example, these might include form fields for your country's postal codes,
phone number formats or government ID numbers.

This code used to live in Django proper -- in django.contrib.localflavor -- but
was separated into standalone packages in Django 1.5 to keep the framework's
core clean.

For a full list of available localflavors, see https://github.com/django/
