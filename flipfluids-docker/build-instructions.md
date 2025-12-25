Build Linux addon

`docker build -t flipfluids-linux -f Dockerfile.linux .`


`docker run --rm \
  -v $(pwd)/output/linux:/opt/flipfluids/build/bl_flip_fluids \
  flipfluids-linux`


📦 Output:

output/linux/flip_fluids_addon.zip


Build Windows addon

`docker build -t flipfluids-windows -f Dockerfile.windows .`


`docker run --rm \
  -v $(pwd)/output/windows:/opt/flipfluids/build/bl_flip_fluids \
  flipfluids-windows`


📦 Output:

output/windows/flip_fluids_addon.zip
