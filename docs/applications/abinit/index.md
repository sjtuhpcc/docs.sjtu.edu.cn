# Abinit

ABINIT is a software suite to calculate the optical, mechanical,
vibrational, and other observable properties of materials. Starting
from the quantum equations of density functional theory, you can build
up to advanced applications with perturbation theories based on DFT,
and many-body Green's functions (GW and DMFT).

NERSC provides modules for [abinit](https://www.abinit.org).

Use the `module avail` command to see what versions are available:

```bash
nersc$ module avail abinit
```

## Example

See the [example jobs page](/jobs/examples/) for additional
examples and infortmation about jobs.

### Edison

```
#!/bin/bash
#SBATCH --qos=regular
#SBATCH --time=01:00:00
#SBATCH --nodes=2
#SBATCH --ntasks-per-node=24
#SBATCH --cpus-per-task=2

module load abinit
srun abinit < example.in
```

## Support

*  [Forum](https://forum.abinit.org)
*  [Wiki](https://wiki.abinit.org/doku.php)
*  [Mailing List](https://sympa-2.sipr.ucl.ac.be/abinit.org)

!!! tip
	If *after* consulting with the above you believe there is an issue
	with the NERSC module, please file a
	[support ticket](https://help.nersc.gov).