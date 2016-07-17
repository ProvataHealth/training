# Provata Health HIPAA Training Docs

This is an overview training of HIPAA, with coverage of key definitions and provisions for the handing of HIPAA-relevant data. The material in this book is intended for individuals who work for organizations that provide technology and technology-enabled services to health systems, payers, physicians, pharma, and other healthcare organizations. It leans more heavily on the use of modern, cloud-based technologies than traditional client side software.

# Getting Started

The Provata Health HIPAA Training docs are built using [Middleman](https://middlemanapp.com/), a static site generator. Please follow the [installation instructions](https://middlemanapp.com/basics/install/) for Middleman before continuing.

Once you have Middleman installed and working you can complete the following to get a working copy of these docs on your local machine:

- `git clone https://github.com/ProvataHealth/training.git`
- `cd training`
- `bundle install`

**Commands:**

- `rake build` generates the static HTML, CSS, and JavaScript files
- `rake run` allows you to view the site locally
- `rake sass` compiles styles changes
- `rake serve_static` runs a simple web server in the build directory

## Attribution

[Catalyze.io](htts://catalyze.io) open-sourced their HIPAA Training [on Github](https://github.com/catalyzeio/policies) and allowed us to use it as a starting point.

This HIPAA Training is licensed under [CC BY-SA 4.0](http://creativecommons.org/licenses/by-sa/4.0/).
