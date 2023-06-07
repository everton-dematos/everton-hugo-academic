---
title: 'seL4 Microkernel for Virtualization Use-Cases: Potential Directions towards a Standard VMM'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Everton de Matos
  - Markku Ahvenjärvi

date: '2022-12-16T00:00:00Z'
doi: ''

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['2']

# Publication name and optional abbreviated publication name.
publication: Electronics
publication_short: Electronics

abstract: Virtualization plays an essential role in providing security to computational systems by isolating execution environments. Many software solutions, called hypervisors, have been proposed to provide virtualization capabilities. However, only a few were designed for being deployed at the edge of the network in devices with fewer computation resources when compared with servers in the Cloud. Among the few lightweight software that can play the hypervisor role, seL4 stands out by providing a small Trusted Computing Base and formally verified components, enhancing its security. Despite today being more than a decade with seL4 microkernel technology, its existing userland and tools are still scarce and not very mature. Over the last few years, the main effort has been to increase the maturity of the kernel itself, and not the tools and applications that can be hosted on top. Therefore, it currently lacks proper support for a full-featured userland Virtual Machine Monitor, and the existing one is quite fragmented. This article discusses the potential directions to a standard VMM by presenting our view of design principles and the feature set needed. This article does not intend to define a standard VMM, we intend to instigate this discussion through the seL4 community.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://doi.org/10.3390/electronics11244201'
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
