---
title: 'Generative AI and electric vehicle service operations in urban and remote areas'
authors:
- Yifan Liu
- Omar I. Asensio
date: '2024-07-01'
publishDate: '2024-07-01'
publication_types:
- conference-paper
publication: '*Data for Policy 2024. Generative AI for Sound Decision-Making*'
doi: 'https://zenodo.org/records/13234565'
url_pdf: 'https://zenodo.org/records/13234565'

abstract: 'For the first time in nearly three decades, the transportation sector is now the largest source of U.S. greenhouse gas emissions. To accelerate climate action, governments are promoting zero emission vehicles (ZEV) policies to accelerate the electrification of cars and trucks, as well as increase equity in access to public charging facilities. However, given the decentralized models of charging station growth, individual station operators set prices and access policies, which have created data interoperability challenges for large-scale analysis of service operations. In this talk, I will describe the use of generative AI and expert specialization to overcome fundamental evaluation challenges with distributed and unstructured digital consumer data, particularly in the context of electric vehicles. By guiding context learning with chain-of-thought prompting, we significantly reduce research evaluation costs with GPT-4, compared with conventional methods of analysis. Using this approach, we evaluate the state of the U.S. electric vehicle charging infrastructure from 2011-2022. The analysis covers 31,527 chargers nationwide, with special emphasis on reliability and distributive-equity issues that impact climate-disadvantaged communities. We uncover evidence that failures in service operations are dominant challenges to the delivery of public charging services. Survival analysis also indicates significantly lower survival rates for charging stations located in climate-disadvantaged communities, particularly for those that are not part of a network with contractual maintenance subscription services. Non-networked stations also face a higher frequency of station losses by consumers. Evidence shows persistent reliability and service provision gaps affecting 22.7 million individuals, particularly in rural communities and urban clusters not expected to be in targeted federal investment zones.'

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