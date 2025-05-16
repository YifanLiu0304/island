---
title: 'Citizen generated intelligence for transport electrification policies'
authors:
- Yifan Liu
- Catharina Hollauer
- M Cade Lawson
- Omar I Asensio
date: '2022-07-01'
publishDate: '2022-07-01'
publication_types:
- conference-paper
publication: '*Data for Policy 2022. Data, Emerging Technologies and Citizens*'
doi: 'https://zenodo.org/records/7296976'

abstract: 'Zero-emissions vehicle policies have been increasingly focused on the deployment and development of electric vehicle (EV) charging infrastructure. One fundamental barrier is the lack of common technology standards which has led to poor data interoperability between networks. For example, EV drivers often face incompatible charging ports or connectors, including closed innovation networks such as Tesla, open networks such as Open Charge Point Protocol (OCPP), and non-networked stations. As a result, large-scale evidence on the quality of the charging experience has been difficult to access and aggregate for decision-makers. In this article, we use machine learning to aggregate citizen-generated data to identify large-scale consumer issues related to infrastructure service provision in the context of electrification in the global transportation sector. Our dataset includes 407,051 publicly-accessible user reviews at 56,291 EV charging stations across the U.S., Europe, and East and Southeast (ESE) Asia from 2010 to 2020. We employ transformer-based natural language processing (NLP) methods to classify topics of discussion from EV users in charging stations globally. We find evidence that the largest closed network Tesla provides EV consumers with better charging service reliability across regions than non-networked stations. Surprisingly, OCPP, which is supposed to reduce barriers to interoperability, provides fare worse charging services than non-networked stations in the U.S. and ESE Asia but not in Europe. We describe long-term evidence on the citizen-generated perspectives for policy evaluation of various technology standards.'

links:
  - name: Abstract
    url: '#'
    css_class: 'abstract-toggle'
  - name: Email me for details
    url: 'mailto:yifan.liu@gatech.edu'
    css_class: 'paper-button'
---

<style>
.paper-button {
  background-color: white !important;
  color: #81c784 !important;
  border: 1px solid #81c784 !important;
}

.abstract-toggle {
  background-color: white !important;
  color: #81c784 !important;
  border: 1px solid #81c784 !important;
}
</style>

<script>
document.addEventListener('DOMContentLoaded', function() {
  var abstractToggle = document.querySelector('.abstract-toggle');
  var abstract = document.querySelector('.article-style');
  
  if (abstract) {
    abstract.style.display = 'none';
  }
  
  if (abstractToggle) {
    abstractToggle.addEventListener('click', function(e) {
      e.preventDefault();
      if (abstract) {
        abstract.style.display = abstract.style.display === 'none' ? 'block' : 'none';
      }
    });
  }
});
</script> 