# Decoding Functional Networks for Visual Categories via Graph Neural Networks

Project page for the ISBI 2026 work by **Shira Karmi, Galia Avidan, and Tammy Riklin-Raviv**.

This repository is based on the **Academic Project Page Template** and has been adapted for a neuroscience / fMRI project page.

ArXiv: `https://arxiv.org/abs/2603.28931`

## Project page URL

If GitHub Pages is enabled from this repository, the page should appear at:

`https://shira8.github.io/Decoding-Functional-Networks-for-Visual-Categories-via-Graph-Neural-Networks/`

## What this page includes

- Hero section with title, authors, and paper links
- Static hero figure
- Overview and abstract
- Dataset and labeling section
- Signed GNN method section
- Results section
- BibTeX block
- Template credit footer

## Files to add

Put these files in the repository before publishing:

### PDFs
- `static/pdfs/paper.pdf`
- `static/pdfs/poster.pdf`
- `static/pdfs/slides.pdf`

### Images
- `static/images/pipeline_overview.png`
- `static/images/experiment_setup.png`
- `static/images/labeling_fusion.png`
- `static/images/model_architecture.png`
- `static/images/tsne_progression.png`
- `static/images/category_networks.png`
- `static/images/social_preview.png`
- `static/images/favicon.ico`

## Recommended image content

### 1. `pipeline_overview.png`
A clean summary figure for the whole project:

`stimulus image -> fMRI responses -> connectivity matrix -> signed graph -> Signed GNN -> explainability`

Best source: your presentation slide with  
**fMRI / Visual stimulus / GNN / Connectivity Matrix / Sparse edge mask / Explainability**.

### 2. `experiment_setup.png`
The experiment flow:

`scanner -> natural image presentation -> button press / task -> brain response`

Best source: your “fMRI Experiment setup” slide.

### 3. `labeling_fusion.png`
A figure showing how labels are generated from COCO masks and captions.

Best source:
- your “How to Label the Data?” slides
- your soft-labeling / semantic evidence vs spatial evidence slide
- or Fig. 1 from the paper

### 4. `model_architecture.png`
A clean architecture figure of the Signed GNN.

Suggested content:
- connectivity matrix input
- split into `A+` and `A-`
- masked graph convolutions
- global pooling
- classifier
- explainability outputs

Best source: your model slide or a cleaned redraw of it.

### 5. `tsne_progression.png`
A 4-panel training progression:
- Epoch 0
- 1/3 training
- 2/3 training
- End of training

Best source: your existing t-SNE figure.

### 6. `category_networks.png`
Category-selective cortical relevance maps.

Suggested content:
- sports
- food
- vehicle
- LH / RH if the layout stays readable

Best source: your poster brain maps or the slide with discovered category-selective networks.

### 7. `social_preview.png`
A 1200x630 image for GitHub / Twitter / LinkedIn previews.

Suggested layout:
- title on the left
- one pipeline graphic
- one brain relevance result panel
- dark clean background

### 8. `favicon.ico`
A simple icon, for example:
- small brain silhouette
- brain + graph nodes
- connectivity matrix icon

## How to publish on GitHub Pages

1. Push the updated files to the repository.
2. Open **Settings -> Pages** in GitHub.
3. Under **Build and deployment**, choose:
   - **Source:** Deploy from a branch
   - **Branch:** `master` (or `main`, whichever your repo uses)
   - **Folder:** `/ (root)`
4. Save.
5. Wait a minute or two for the site to build.

## Main file to edit

Most content is controlled in:

- `index.html`

## Notes

- The page already includes the arXiv link; add Google Scholar later if you want.
- Keep the footer credit block, since the original template asks for it.
- Compress large PNG files before pushing them.

## Suggested section order

1. Title + links
2. Static hero figure
3. Overview
4. Abstract
5. Dataset and labeling
6. From fMRI to signed graphs
7. Results
8. Key findings
9. BibTeX

## Acknowledgment

This page was built using the [Academic Project Page Template](https://github.com/eliahuhorwitz/Academic-project-page-template), adopted from the Nerfies project page.
