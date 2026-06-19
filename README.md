# JavaScript Import and Export
There are many ways to use JavaScript import and export. It can get confusing.

## Default export
Only one default export allowed per module.

  // module "cube.js"
  export default function cube(x) {
    return x * x * x;
  }

  // "main.js"
  import cube from "./cube.js"
  
  console.log(cube(3)); // 27



## The basic export format
  export function celsius_to_fahrenheit(x) {
    return (x * 1.8) + 32
  }
