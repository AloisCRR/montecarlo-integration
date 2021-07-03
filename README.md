# Montecarlo simulation (Integral)

Basic project to test PyQt.

## Run Locally

1. Install:

   - [Python](https://www.python.org/downloads/) (3.7+)
   - [Pipenv](https://pipenv-es.readthedocs.io/)

1. Clone the project:

   ```bash
   git clone https://github.com/AloisCRR/montecarlo-integration.git
   ```

1. Go to the project directory:

   ```bash
   cd montecarlo-integration
   ```

1. Install dependencies:

   ```bash
   pipenv install
   ```

1. Generate python GUI from PyQt5:

   ```bash
   python3 -m PyQt5.uic.pyuic -x src/interfaz.ui -o src/interfaz.py
   ```

1. Run the GUI:

   ```bash
   python3 src/interfaz.py
   ```

## Screenshots

<p align="center">
  <img src="https://github.com/AloisCRR/montecarlo-simulation-integral/blob/master/screenshots/screenshot.png" alt="Screenshot #1">
</p>

## Appendix

- Useful links
  - [Integración Monte Carlo (clásica)](https://rubenfcasal.github.io/simbook/integraci%C3%B3n-monte-carlo-cl%C3%A1sica.html)
  - [Monte Carlo Integration in Python](http://barnesanalytics.com/monte-carlo-integration-in-python)
