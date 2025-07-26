# AlumniEI FEUP Website

This is the official website for AlumniEI-FEUP, the alumni association for Computer and Informatics Engineering at the Faculty of Engineering, University of Porto (FEUP).

**Live Site:** [https://alumniei.github.io/](https://alumniei.github.io/)

---

## Development

This website is built with Jekyll and hosted on GitHub Pages.

### Prerequisites

- Ruby
- Bundler

### Running Locally

1.  **Clone the repository:**
    ```bash
    git clone https://github.com/alumniei/alumniei.github.io.git
    cd alumniei.github.io
    ```

2.  **Install dependencies:**
    The `Gemfile` specifies the required gems. Install them by running:
    ```bash
    bundle install
    ```

3.  **Start the Jekyll server:**
    ```bash
    bundle exec jekyll serve
    ```

4.  Open your browser and navigate to `http://localhost:4000`. The site will automatically reload when you make changes to the source files.

## Deployment

This site is automatically deployed by GitHub Pages. Any changes pushed to the `main` branch will trigger a new build and deployment. The manual deployment steps are not necessary.

## Contributing

Contributions are welcome! If you have a suggestion or want to fix a bug, please feel free to open an issue or submit a pull request.

1.  Fork the repository.
2.  Create a new branch (`git checkout -b feature/your-feature-name`).
3.  Make your changes and commit them.
4.  Push to your forked repository.
5.  Open a Pull Request against the `main` branch of this repository.
