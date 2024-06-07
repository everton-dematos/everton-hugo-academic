---
title: 'Integrating VirtIO and QEMU on seL4 for Enhanced Devices Virtualization Support'

# Authors
# If you created a profile for a user (e.g. the default `admin` user), write the username (folder name) here
# and it will be replaced with their full name and linked to their profile.
authors:
  - Everton de Matos
  - Conor Lennon
  - Eduardo K. Viegas
  - Markku Ahvenjarvi
  - Hannu Lyytinen
  - Ivan Kuznetsov
  - Joonas Onatsu
  - Anh Huy Bui

date: '2023-11-01T00:00:00Z'
doi: ''

# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ['1']

# Publication name and optional abbreviated publication name.
publication: 22nd IEEE International Conference On Trust, Security And Privacy In Computing And Communications
publication_short: TrustCom 2023

abstract: Virtualization is a crucial technology for consolidating workloads and improving resource utilization in modern computing systems. seL4 is a small TCB (Trusted Computing Base) microkernel that can be used as a hypervisor to provide virtualization features. However, providing standard device interfaces to it remains a significant challenge in achieving secure and high-performance virtualization solutions for critical systems. To address this challenge, this paper proposes an approach that leverages the VirtIO standard through QEMU to provide a secure and efficient device virtualization solution for seL4. The feature takes advantage of seL4’s isolation guarantees and enables sharing of complex devices for multiple virtual machines, combined with the efficient communication interface provided by the VirtIO standard. We implemented and evaluated the approach using a set of benchmarks. The proposed approach leverages the VirtIO standard through QEMU on top of the seL4, aiming to offer a virtualization solution that accelerates development speed and enhances architectural flexibility by eliminating the need for native drivers.

tags: []

# Display this page in the Featured widget?
featured: true

# Custom links (uncomment lines below)
# links:
# - name: Custom Link
#   url: http://example.org

url_pdf: 'https://doi.org/10.1109/TrustCom60117.2023.00149'
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
