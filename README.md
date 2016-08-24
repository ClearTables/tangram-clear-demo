# Tangram and ClearTables Demo

## Install
- [Import data with osm2pgsql](https://github.com/pnorman/ClearTables#usage) to the database `gis`
- Run [osm-clear.tm2source/get-shapefiles.sh](osm-clear.tm2source/get-shapefiles.sh)
- Install the `z()` function in the database with `psql -d gis -f z.sql`
- Open with [Kosmtik](https://github.com/kosmtik/kosmtik)
- Point the Tangram scene file at your Kosmtik tiles
