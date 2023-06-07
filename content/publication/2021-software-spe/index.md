---
title: 'A lightweight virtualization model to enable edge computing in deeply embedded systems'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Ramão Tiago Tiburski
  - Carlos Roberto Moratelli
  - Sergio F. Johann
  - Everton de Matos
  - Fabiano Hessel

date: '2021-03-18T00:00:00Z'
doi: ''

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: Software Practice and Experience
publication_short: Software Practice and Experience

abstract: Edge computing paradigm enables moving Internet of Things (IoT) applications from the Cloud to the edge of the network. Modern software engineering approaches are adhering to microservices to enable the deployment of such applications on edge devices. Microservices consist of the disaggregation of an application into smaller pieces that operate independently. Recent works have explored microservices packaged into containers and advocate that containers result in a reduced footprint and avoid the unwanted overhead caused by traditional virtualization. However, containers cannot be used in many deeply embedded systems (DES) due to an underlying operating system's (OSs) requirement. DES are edge devices with minimal resources regarding storage, memory, and processing power. Thus, they cannot afford large and sophisticated OSs. This article presents the Hellfire hypervisor, a lightweight virtualization implementation that enables separation and improves security in IoT applications on DES. Our proposal simplifies the traditional hypervisor approach and reaches devices where the existing techniques fail. The results show that the proposed model has a small footprint of 23 KB while keeping a low average virtualization overhead of 0.62% for multiple virtual machines execution.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://doi.org/10.1002/spe.2968'
url_code: ''
url_dataset: ''
url_poster: ''
url_project: ''
url_slides: ''
url_source: ''
url_video: ''

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder.
image:
  caption: ''
  focal_point: ''
  preview_only: false

---
