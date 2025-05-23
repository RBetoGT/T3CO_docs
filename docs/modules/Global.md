# Table of Contents

* [t3co/constants/Global](#t3co/constants/Global)
  * [DieselGalPerGasGal](#t3co/constants/Global.DieselGalPerGasGal)
  * [kgH2\_per\_gge](#t3co/constants/Global.kgH2_per_gge)
  * [mps\_to\_mph](#t3co/constants/Global.mps_to_mph)
  * [m\_to\_mi](#t3co/constants/Global.m_to_mi)
  * [set\_tco\_intermediates](#t3co/constants/Global.set_tco_intermediates)
  * [set\_tco\_results](#t3co/constants/Global.set_tco_results)
  * [kg\_to\_lbs](#t3co/constants/Global.kg_to_lbs)
  * [lbs\_to\_kgs](#t3co/constants/Global.lbs_to_kgs)
  * [not\_falsy](#t3co/constants/Global.not_falsy)

<a id="t3co/constants/Global"></a>

# t3co/constants/Global

Global constants
Stores paths to directories used for input files, as well as constants referenced throughout the code base

<a id="t3co/constants/Global.DieselGalPerGasGal"></a>

#### DieselGalPerGasGal

energy equivalent gallons of diesel per 1 gallon gas

<a id="t3co/constants/Global.kgH2_per_gge"></a>

#### kgH2\_per\_gge

https://epact.energy.gov/fuel-conversion-factors for Hydrogen

<a id="t3co/constants/Global.mps_to_mph"></a>

#### mps\_to\_mph

1 mps = 2.23694 mph

<a id="t3co/constants/Global.m_to_mi"></a>

#### m\_to\_mi

1 m = 0.000621371 mi

<a id="t3co/constants/Global.set_tco_intermediates"></a>

#### set\_tco\_intermediates

```python
def set_tco_intermediates()
```

This function sets path for TCO_INTERMEDIATES to save tsv files

<a id="t3co/constants/Global.set_tco_results"></a>

#### set\_tco\_results

```python
def set_tco_results()
```

This function sets path for TCO_RESULTS

<a id="t3co/constants/Global.kg_to_lbs"></a>

#### kg\_to\_lbs

```python
def kg_to_lbs(kgs: float) -> float
```

This function converts kg to lb

**Arguments**:

- `kgs` _float_ - mass in kg
  

**Returns**:

- `(float)` - mass in pounds

<a id="t3co/constants/Global.lbs_to_kgs"></a>

#### lbs\_to\_kgs

```python
def lbs_to_kgs(lbs: float) -> float
```

This function converts lb to kg

**Arguments**:

- `lbs` _float_ - mass in pounds
  

**Returns**:

- `(float)` - mass in kg

<a id="t3co/constants/Global.not_falsy"></a>

#### not\_falsy

```python
def not_falsy(var: float) -> bool
```

This function returns True to verify that var is NOT falsy: not in [None, np.nan, 0, False]


**Arguments**:

- `var` _float_ - variable to check
  

**Returns**:

- `(bool)` - True if not in [None, 0, False]

