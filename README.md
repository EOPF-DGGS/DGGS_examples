# DGGS Examples

[![Jupyter Book](https://img.shields.io/badge/docs-jupyter--book-orange.svg)](https://eopf-dggs.github.io/DGGS_examples/)
[![MIT License](https://img.shields.io/badge/License-MIT-blue.svg)](https://opensource.org/licenses/MIT)
[![CC BY 4.0 License](https://img.shields.io/badge/License-CC%20BY%204.0-lightgrey.svg)](http://creativecommons.org/licenses/by/4.0/)

A collection of examples and documentation for Discrete Global Grid Systems (DGGS) in Earth Observation, developed as part of the [GRID4EARTH](https://www.grid4earth.eu/) ESA-funded project.

## 📖 About

This repository provides practical examples demonstrating DGGS concepts and applications for geospatial data analysis. The examples focus on HEALPix-based implementations and demonstrate best practices for metadata encoding, data processing, and integration with modern scientific Python workflows.

## 🌐 Live Documentation

The complete documentation is available as an interactive Jupyter Book:
**[https://eopf-dggs.github.io/DGGS_examples/](https://eopf-dggs.github.io/DGGS_examples/)**

The website is automatically built and deployed using Jupyter Book 2.x and GitHub Actions.

## 🎯 Project Context

This work is developed as part of the **[GRID4EARTH](https://eopf-dggs.github.io)** project funded by ESA, focusing on exploring DGGS (Discrete Global Grid System) for Earth Observation and Destination Earth data. The project aims to provide practical guidance and examples for implementing DGGS in scientific workflows.

## 🔧 Key Technologies

- **DGGS Implementation**: HEALPix (Hierarchical Equal Area isoLatitude Pixelisation)
- **Data Processing**: xdggs, xarray, and scientific Python ecosystem
- **Data Storage**: Zarr format for cloud-optimized arrays
- **Documentation**: Jupyter Book 2.x with MyST Markdown
- **Deployment**: GitHub Actions with automated CI/CD

## 📚 Repository Structure

- **`notebooks/`** - Jupyter notebooks with DGGS examples and tutorials
- **`myst.yml`** - Jupyter Book configuration
- **`.github/workflows/`** - Automated deployment and testing
- **`.binder/`** - Environment configuration for reproducible execution

## 🚀 Getting Started

### Prerequisites
- Python 3.8+
- Required packages specified in `.binder/environment.yml`

### Local Development

1. **Clone the repository**:
   ```bash
   git clone https://github.com/EOPF-DGGS/DGGS_examples.git
   cd DGGS_examples
   ```

2. **Set up environment**:
   ```bash
   mamba env create -f .binder/environment.yml
   mamba activate eopf-zarr
   ```

3. **Install Jupyter Book**:
   ```bash
   pip install --pre "jupyter-book==2.*"
   ```

4. **Build documentation locally**:
   ```bash
   jupyter-book build --html
   ```

### Running Examples

Examples can be executed through:
- **Local Jupyter**: After setting up the environment
- **Binder**: Interactive execution via the online documentation

## 🌍 DGGS Applications

DGGS provides advantages for geospatial data analysis including:

- **Equal-area preservation** for accurate global statistics
- **Hierarchical indexing** for efficient multi-scale analysis
- **Cloud-native compatibility** with modern data formats
- **Cross-domain applicability** across Earth science disciplines

## 📄 Licensing

This repository uses a dual licensing approach:

- **Code & Notebooks**: [MIT License](LICENSE) - Permissive license for software components
- **Documentation & Content**: [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) - Attribution license for educational materials

## 🤝 Contributing

We welcome contributions to improve examples and documentation. Please:

1. Fork the repository
2. Create a feature branch
3. Add your improvements
4. Ensure examples run successfully
5. Submit a pull request

### GRID4EARTH Consortium
- **IFREMER** (France) - Lead institution
- **Simula Research Laboratory** (Norway)
- **CNRS** (France)
- **University of Tartu** (Estonia)
- **GEORODE** (Belgium)

## 🏆 Funding & Acknowledgments

This work is funded by the European Space Agency (ESA) under the Digital Twin Earth (DTE) Framework initiative.

**ESA Contract**: 4000147951/25/I-NS  
**Technical Officer**: Vincent Dumoulin

## 📞 Support & Contact

- **Issues**: Use GitHub Issues for bug reports or feature requests
- **Discussions**: Use GitHub Discussions for questions and community interaction
- **Email**: Contact the lead author for project-specific inquiries

## 🔗 Related Resources

- [GRID4EARTH Project Website](https://www.grid4earth.eu/)
- [xdggs Python Library](https://github.com/xarray-contrib/xdggs)
- [HEALPix Documentation](https://healpix.sourceforge.io/)
- [Jupyter Book Documentation](https://jupyterbook.org/)

---

*Advancing geospatial data analysis through Discrete Global Grid Systems.*
