All the code and examples here were created using the information in
[rspatial.org](https://rspatial.org/raster/rs/1-introduction.html)

## Downloading example data

    if (!file.exists('data/rs/samples.rds')) {
        download.file('https://biogeo.ucdavis.edu/data/rspatial/rsdata.zip', dest = 'data/rsdata.zip')
        unzip('data/rsdata.zip', exdir = 'data')
    }
