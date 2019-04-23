+++
title = "Influence of Frequency Bands in EEG Signal to Predict User Intent"
date = 2015-09-01T00:00:00

# Authors. Comma separated list, e.g. `["Melynda Schreiber", "Mitja Trkov, Andrew Merryweather"]`.
authors = ["Melynda Schreiber", "Mitja Trkov, Andrew Merryweather"]

# Publication type.
# Legend:
# 0 = Uncategorized
# 1 = Conference paper
# 2 = Journal article
# 3 = Preprint / Working Paper
# 4 = Report
# 5 = Book
# 6 = Book section
# 7 = Thesis
# 8 = Patent
publication_types = ["1"]

# Publication name and optional abbreviated version.
publication = "*Conference Proceedings of Neural Engineering, 1*(1)"
publication_short = ""

# Abstract.
abstract = "Decoding motor user intent using electroencephalography (EEG) sensors may aid individuals with limited upper extremity mobility. Researchers have successfully used Filter Bank Common Spatial Pattern(FBCSP) and Linear Discriminant Analysis (LDA) to predict user intent from EEG. Frequency bands between 8 to 40 Hz, with 4 Hz intervals are used as inputs to FBCSP classification. While this range includes the commonly used alpha (8–13 Hz) and beta (16–24 Hz) frequency bands, it excludes the delta band (0.3–3 Hz). The delta band has been shown to contain information regarding user intent. This paper investigates the accuracy of predicting user intent to reach and lift when modifying FBCSP to include combinations of alpha, beta and delta bands. This comparison was performed for clinical (32-electrodes) and commercial (12-electrodes) EEG electrode configurations using the WAY-EEG-GAL dataset. The simulated commercial configuration placement mimicked those from the Emotiv Epoc+. We predicted intent to reach(HandStart) and lift a block (LiftOff) by comparing the EEG signal to rest conditions. Intent classification accuracy is the accuracy to predict the future event before the event occurs. Maximum classification accuracy is the maximum accuracy to predict the event during the region of interest (-2.5, -2.0 sec.). Intent classification accuracy of 80.2% and 76.7% were achieved for the clinical and commercial configurations, respectively. Maximum classification accuracy of 85.9% and 83.0% were achieved for the clinical and commercial configuration, respectively. The combination of all three bands outperformed alpha-beta-only and delta-only by 0.9% and 9.9% for the clinical and 4.0% and 4.3% for the commercial for maximum classification accuracy. Using the combination of bands resulted in a maximum classification above 80% for the commercial configuration. These results suggest that including the delta frequency band can help improve the accuracy of user intent in clinical and commercial headsets."

# Summary. An optional shortened abstract.
# summary = "Lorem ipsum dolor sit amet, consectetur adipiscing elit. Duis posuere tellus ac convallis placerat. Proin tincidunt magna sed ex sollicitudin condimentum."

# Digital Object Identifier (DOI)
doi = ""

# Is this a featured publication? (true/false)
featured = false

# Tags (optional).
#   Set `tags = []` for no tags, or use the form `tags = ["A Tag", "Another Tag"]` for one or more tags.
tags = ["Source Themes"]

# Projects (optional).
#   Associate this publication with one or more of your projects.
#   Simply enter your project's folder or file name without extension.
#   E.g. `projects = ["deep-learning"]` references 
#   `content/project/deep-learning/index.md`.
#   Otherwise, set `projects = []`.
projects = []

# Slides (optional).
#   Associate this publication with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references 
#   `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
slides = "example"

# Links (optional).
url_pdf = ""
url_code = ""
url_dataset = "https://www.kaggle.com/c/grasp-and-lift-eeg-detection"
url_project = ""
url_slides = ""
url_video = ""
url_poster = ""
url_source = ""

# Custom links (optional).
#   Uncomment line below to enable. For multiple links, use the form `[{...}, {...}, {...}]`.
# links = [{name = "Custom Link", url = "http://example.org"}]

# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
[image]
  # Caption (optional)
  caption = "Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)"

  # Focal point (optional)
  # Options: Smart, Center, TopLeft, Top, TopRight, Left, Right, BottomLeft, Bottom, BottomRight
  focal_point = ""
+++

{{% alert note %}}
Supplementary notes can be added here, including [code and math](https://sourcethemes.com/academic/docs/writing-markdown-latex/).
{{% /alert %}}