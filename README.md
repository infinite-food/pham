# Pre-revenue Hardware Achievement Metric (PHAM)

This metric was designed by [Infinite Food](http://infinite-food.com/) for [YCombinator Startup School 2018](http://startupschool.org) to provide what is hopefully a simple, standard, generally applicable progress metric for pre-revenue hardware startups.

## Philosophy

The philosophy of the metric is to be:
 * Generally applicable
 * Simple and easy to understand
 * Iterative

In other words, we seek a reusable approach to the capturing of common types of progress in hardware development that can provide a moving metric to track and motivate progress over time, regardless of the specific nature of the hardware project.

## Scope

Although intended for hardware, it can be extended to cover business development, software and other aspects of a hardware related business simply by defining non-hardware modules.

## Output

PHAM produces progress metrics of to two types:
 * Functionality achieved
 * Readiness for manufacturing

Each of these metrics can be expressed as percentages, for example a project may be "75% functional and 40% ready for manufacturing".

In shorthand we can express the same as PHAM 75/40.

## Calculating your PHAM

 * First, __divide your product in to modules.__ 
   * These can be physical modules, components or subassemblies or can be logical or business-related modules that are part of your target offering.
     * For example, if your hardware requires an app, that may be a module.
     * A typical methodology is to use github repos as your modules.
 * Now __rate each module for functionality and readiness for manufacturing__. 
   * __Functionality__ (Each point scores 25% or a fraction thereof)
     * Design requirements documented
     * Has been produced and assembled
     * Has been tested (solo) and meets design requirements
     * Has been tested (installed in situ with all adjacent modules and subsystems within a prototype unit) and confirmed to meet design requirements under these conditions
   * __Readiness for manufacturing__ (Each point scores 10% or a fraction thereof)
     * Functional completion (as above)
     * Design documented (eg. 3D models, design discussion such as component selection justification, etc.)
     * BOM list written
     * BOM per-material cost estimation completed at initial manufacturing volumes
     * Assembly process documented (steps, tools, space requirements, inputs, outputs, etc.)
     * Assembly process idiot-proofed ([poka-yoke](https://en.wikipedia.org/wiki/Poka-yoke); multiple unskilled idiot volunteers did it right first time)
     * Post-assembly testing procedures documented
     * Maintenance schedule designed and documented (if applicable)
     * Probable lifetime documented (if possible to estimate)
     * Probably failure modes declared (and any options to reduce them, eg. by upgrading components in subsequent design iteration)
 * Calculate the total.

## Example

Please see the [LibreOffice Calc template](pham-template) for an example.

## License

[MIT](LICENSE)
