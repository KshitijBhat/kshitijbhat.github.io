---
title: "GLiDR: Topologically Regularized Graph Generative Network for Sparse LiDAR Point Clouds"
authors:
- Prashant Kumar
- admin
- Vedang Bhupesh Shenvi Nadkarni
- Prem Kalra
date: "2024-06-22T00:00:00Z"
doi: "10.1109/CVPR52733.2024.01435"

# Schedule page publish date (NOT publication's date).
publishDate: "2023-09-16T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
# Publication type.
# Legend: 0 = Uncategorized; 1 = Conference paper; 2 = Journal article;
# 3 = Preprint / Working Paper; 4 = Report; 5 = Book; 6 = Book section;
# 7 = Thesis; 8 = Patent
publication_types: ["1"]

# Publication name and optional abbreviated publication name.
publication: "Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition"
publication_short: "Proceedings of the IEEE/CVF Conference on Computer Vision and Pattern Recognition"

abstract: 'Sparse LiDAR point clouds cause severe loss of detail of static structures and reduce the density of static points available for navigation. Reduced density can be detrimental to navigation under several scenarios. We observe that despite high sparsity in most cases the global topology of LiDAR outlining the static structures can be inferred. We utilize this property to obtain a backbone skeleton of a LiDAR scan in the form of a single connected component that is a proxy to its global topology. We utilize the backbone to augment new points along static structures to overcome sparsity. Newly introduced points could correspond to existing static structures or to static points that were earlier obstructed by dynamic objects. To the best of our knowledge we are the first to use such a strategy for sparse LiDAR point clouds. Existing solutions close to our approach fail to identify and preserve the global static LiDAR topology and generate sub-optimal points. We propose GLiDR a Graph Generative network that is topologically regularized using 0-dimensional Persistent Homology (PH) constraints. This enables GLiDR to introduce newer static points along a topologically consistent global static LiDAR backbone. GLiDR generates precise static points using 32x sparser dynamic scans and performs better than the baselines across three datasets. GLiDR generates a valuable byproduct-an accurate binary segmentation mask of static and dynamic objects that are helpful for navigation planning and safety in constrained environments. The newly introduced static points allow GLiDR to outperform LiDAR-based navigation using SLAM in several settings.'

# Summary. An optional shortened abstract.
summary: 'Sparse LiDAR point clouds cause severe loss of detail of static structures and reduce the density of static points available for navigation. Reduced density can be detrimental to navigation under several scenarios. We observe that despite high sparsity in most cases the global topology of LiDAR outlining the static structures can be inferred. We utilize this property to obtain a backbone skeleton of a LiDAR scan in the form of a single connected component that is a proxy to its global topology. We utilize the backbone to augment new points along static structures to overcome sparsity. Newly introduced points could correspond to existing static structures or to static points that were earlier obstructed by dynamic objects. To the best of our knowledge we are the first to use such a strategy for sparse LiDAR point clouds. Existing solutions close to our approach fail to identify and preserve the global static LiDAR topology and generate sub-optimal points. We propose GLiDR a Graph Generative network that is topologically regularized using 0-dimensional Persistent Homology (PH) constraints. This enables GLiDR to introduce newer static points along a topologically consistent global static LiDAR backbone. GLiDR generates precise static points using 32x sparser dynamic scans and performs better than the baselines across three datasets. GLiDR generates a valuable byproduct-an accurate binary segmentation mask of static and dynamic objects that are helpful for navigation planning and safety in constrained environments. The newly introduced static points allow GLiDR to outperform LiDAR-based navigation using SLAM in several settings.'

tags:
 - Computer Vision
 - Deep Learning
featured: true

# links:
url_pdf: https://openaccess.thecvf.com/content/CVPR2024/papers/Kumar_GLiDR_Topologically_Regularized_Graph_Generative_Network_for_Sparse_LiDAR_Point_CVPR_2024_paper.pdf
url_code: 'https://github.com/KshitijBhat/GLiDR-code'
url_dataset: ''
url_poster: ''
url_project: 'https://kshitijbhat.github.io/glidr/'
url_source: ''
url_video: 'https://www.youtube.com/watch?v=oqJLJL-mYqg'

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: ''
  focal_point: ""
  preview_only: false

# Associated Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `internal-project` references `content/project/internal-project/index.md`.
#   Otherwise, set `projects: []`.
projects: ['glidr']

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides: "example"` references `content/slides/example/index.md`.
#   Otherwise, set `slides: ""`.
slides: ""

# Other options
show_related: true

---
<!-- ### Example figure
![Median peak ground acceleration (PGA) for each scenario earthquake, from left to right: 2021 MW7.2 Nippes inHaiti, 2016 MW7.0 Kumamoto in Japan, and 2015 MW7.8 Gorkha in Nepal. Available recording station PGA values are shownas triangles, which were used to condition the simulated ground motion fields.](publication/journal-article/2024_benchmarking_predictions.png "Median peak ground acceleration (PGA) for each scenario earthquake, from left to right: 2021 MW7.2 Nippes inHaiti, 2016 MW7.0 Kumamoto in Japan, and 2015 MW7.8 Gorkha in Nepal. Available recording station PGA values are shownas triangles, which were used to condition the simulated ground motion fields.") -->
