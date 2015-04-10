drupal-7.fix_language_negociation
=================================

Get browser language detection to work properly for anonymous users, see https://www.drupal.org/node/2257843

Usage :  
enable this module,  
clear all caches,  
go to admin/config/regional/language/configure and press "Save settings" once (this will rebuild the variable 'language_negotiation_language').