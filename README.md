# Project repo

This repository contains example simulations of a **Batch Elution** process using **CADET-Process** and **CADET-RDM**. A two-component system with a **Langmuir isotherm** binding model and a **LumpedRateModelWithoutPores** unit operation model is simulated. Following this, the operating conditions are **optimized** to maximize process performance. This can be achieved by combining multiple parameters into a single objective (`optimization_single.py`) or by setting up a multi-objective problem (`optimization_multi.py`).


---

## Authors

* Johannes Schmölder
* Katharina Paul
* Ronald Jäpel
* Hannah Lanzrath

---

## Running the Example Simulation

1. Clone this repository.
2. Set up the environment using the `environment.yml` file.
3. Run the simulation:

   ```bash
   python main.py
   ```

The results will be stored in the `src` folder inside the `output` directory.

> **Note**: Running `cadet-rdm` requires [**Git LFS**](https://git-lfs.com/), which needs to be installed separately.
>
> * **Ubuntu/Debian**:
>
>   ```bash
>   sudo apt-get install git-lfs
>   git lfs install
>   ```
>
> * **macOS** (with Homebrew):
>
>   ```bash
>   brew install git-lfs
>   git lfs install
>   ```
>
> * **Windows**:
>   Download and install from [https://git-lfs.com](https://git-lfs.com)

---

## Output Repository

The output data for this case study can be found here:
[Link to Output Repository](https://github.com/cadet/RDM-Example-Batch-Elution-Output)
