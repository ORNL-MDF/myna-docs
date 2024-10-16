---
title: Components and Applications
layout: default
nav_order: 4
---

# Myna Components and Applications
{: .no_toc }

## Table of Contents
{: .no_toc .text-delta }

1. TOC
{:toc}

Myna version: 1.1.0.dev0

This page contains the list of available classes within Myna for workflow components, input and output data, and applications.

## Workflow Component Classes

- [**Component**](https://github.com/ORNL-MDF/Myna/tree/main/myna/core/components/component.py)
  - [ComponentSolidification](https://github.com/ORNL-MDF/Myna/tree/main/myna/core/components/component_solidification.py)
    - [ComponentSolidificationPart](https://github.com/ORNL-MDF/Myna/tree/main/myna/core/components/component_solidification.py)
    - [ComponentSolidificationRegion](https://github.com/ORNL-MDF/Myna/tree/main/myna/core/components/component_solidification.py)
      - [ComponentSolidificationPartSTL](https://github.com/ORNL-MDF/Myna/tree/main/myna/core/components/component_solidification.py)
      - [ComponentSolidificationRegionSTL](https://github.com/ORNL-MDF/Myna/tree/main/myna/core/components/component_solidification.py)
      - [ComponentSolidificationPartReduced](https://github.com/ORNL-MDF/Myna/tree/main/myna/core/components/component_solidification.py)
      - [ComponentSolidificationRegionReduced](https://github.com/ORNL-MDF/Myna/tree/main/myna/core/components/component_solidification.py)
  - [ComponentMicrostructure](https://github.com/ORNL-MDF/Myna/tree/main/myna/core/components/component_microstructure.py)
    - [ComponentMicrostructurePart](https://github.com/ORNL-MDF/Myna/tree/main/myna/core/components/component_microstructure.py)
      - [ComponentMicrostructureRegion](https://github.com/ORNL-MDF/Myna/tree/main/myna/core/components/component_microstructure.py)
        - [ComponentMicrostructureRegionSlice](https://github.com/ORNL-MDF/Myna/tree/main/myna/core/components/component_microstructure.py)
  - [ComponentRVE](https://github.com/ORNL-MDF/Myna/tree/main/myna/core/components/component_rve.py)
  - [ComponentCentroidRVE](https://github.com/ORNL-MDF/Myna/tree/main/myna/core/components/component_rve.py)
  - [ComponentCluster](https://github.com/ORNL-MDF/Myna/tree/main/myna/core/components/component_cluster.py)
    - [ComponentClusterSolidification](https://github.com/ORNL-MDF/Myna/tree/main/myna/core/components/component_cluster.py)
    - [ComponentClusterSupervoxel](https://github.com/ORNL-MDF/Myna/tree/main/myna/core/components/component_cluster.py)
  - [ComponentMesh](https://github.com/ORNL-MDF/Myna/tree/main/myna/core/components/component_mesh.py)
    - [ComponentPartMesh](https://github.com/ORNL-MDF/Myna/tree/main/myna/core/components/component_mesh.py)
      - [ComponentPartMeshVTK](https://github.com/ORNL-MDF/Myna/tree/main/myna/core/components/component_mesh.py)
  - [ComponentTemperature](https://github.com/ORNL-MDF/Myna/tree/main/myna/core/components/component_temperature.py)
    - [ComponentTemperaturePart](https://github.com/ORNL-MDF/Myna/tree/main/myna/core/components/component_temperature.py)
  - [ComponentMeltPoolGeometry](https://github.com/ORNL-MDF/Myna/tree/main/myna/core/components/component_melt_pool_geometry.py)
    - [ComponentMeltPoolGeometryPart](https://github.com/ORNL-MDF/Myna/tree/main/myna/core/components/component_melt_pool_geometry.py)

## Output File Classes

- [**File**](https://github.com/ORNL-MDF/Myna/tree/main/myna/core/files/file.py)
  - [FileRegion](https://github.com/ORNL-MDF/Myna/tree/main/myna/core/files/file_region.py)
  - [FileGV](https://github.com/ORNL-MDF/Myna/tree/main/myna/core/files/file_gv.py)
  - [FileID](https://github.com/ORNL-MDF/Myna/tree/main/myna/core/files/file_id.py)
  - [FileReducedSolidification](https://github.com/ORNL-MDF/Myna/tree/main/myna/core/files/file_reduced_solidification.py)
  - [FileVTK](https://github.com/ORNL-MDF/Myna/tree/main/myna/core/files/file_vtk.py)
  - [FileTemperature](https://github.com/ORNL-MDF/Myna/tree/main/myna/core/files/file_temperature.py)
  - [FileMeltPoolGeometry](https://github.com/ORNL-MDF/Myna/tree/main/myna/core/files/file_melt_pool_geometry.py)

## Input Metadata and File Classes

- [**BuildMetadata**](https://github.com/ORNL-MDF/Myna/tree/main/myna/core/metadata/data.py)
  - [PartMetadata](https://github.com/ORNL-MDF/Myna/tree/main/myna/core/metadata/data.py)
    - [SpotSize](https://github.com/ORNL-MDF/Myna/tree/main/myna/core/metadata/data_spot_size.py)
  - [Material](https://github.com/ORNL-MDF/Myna/tree/main/myna/core/metadata/data_material.py)
    - [LaserPower](https://github.com/ORNL-MDF/Myna/tree/main/myna/core/metadata/data_laser_power.py)
  - [LayerThickness](https://github.com/ORNL-MDF/Myna/tree/main/myna/core/metadata/data_layer_thickness.py)
  - [Preheat](https://github.com/ORNL-MDF/Myna/tree/main/myna/core/metadata/data_preheat.py)
- [**BuildFile**](https://github.com/ORNL-MDF/Myna/tree/main/myna/core/metadata/file.py)
  - [BuildLayerPartsetFile](https://github.com/ORNL-MDF/Myna/tree/main/myna/core/metadata/file.py)
  - [PartFile](https://github.com/ORNL-MDF/Myna/tree/main/myna/core/metadata/file.py)
    - [LayerFile](https://github.com/ORNL-MDF/Myna/tree/main/myna/core/metadata/file.py)
      - [Scanpath](https://github.com/ORNL-MDF/Myna/tree/main/myna/core/metadata/file_scanpath.py)
    - [STL](https://github.com/ORNL-MDF/Myna/tree/main/myna/core/metadata/file_stl.py)
    - [PartIDMap](https://github.com/ORNL-MDF/Myna/tree/main/myna/core/metadata/file_part_id_map.py)

## Applications

- [**thesis**](https://github.com/ORNL-MDF/Myna/tree/main/myna/application/thesis)
  - [melt_pool_geometry_part](https://github.com/ORNL-MDF/Myna/tree/main/myna/application/thesis/melt_pool_geometry_part)
  - [solidification_part](https://github.com/ORNL-MDF/Myna/tree/main/myna/application/thesis/solidification_part)
  - [temperature_part](https://github.com/ORNL-MDF/Myna/tree/main/myna/application/thesis/temperature_part)
- [**rve**](https://github.com/ORNL-MDF/Myna/tree/main/myna/application/rve)
  - [rve_selection](https://github.com/ORNL-MDF/Myna/tree/main/myna/application/rve/rve_selection)
  - [rve_part_center](https://github.com/ORNL-MDF/Myna/tree/main/myna/application/rve/rve_part_center)
- [**openfoam**](https://github.com/ORNL-MDF/Myna/tree/main/myna/application/openfoam)
  - [mesh_part_vtk](https://github.com/ORNL-MDF/Myna/tree/main/myna/application/openfoam/mesh_part_vtk)
- [**bnpy**](https://github.com/ORNL-MDF/Myna/tree/main/myna/application/bnpy)
  - [cluster_supervoxel](https://github.com/ORNL-MDF/Myna/tree/main/myna/application/bnpy/cluster_supervoxel)
  - [cluster_solidification](https://github.com/ORNL-MDF/Myna/tree/main/myna/application/bnpy/cluster_solidification)
- [**exaca**](https://github.com/ORNL-MDF/Myna/tree/main/myna/application/exaca)
  - [microstructure_region](https://github.com/ORNL-MDF/Myna/tree/main/myna/application/exaca/microstructure_region)
  - [microstructure_region_slice](https://github.com/ORNL-MDF/Myna/tree/main/myna/application/exaca/microstructure_region_slice)
- [**additivefoam**](https://github.com/ORNL-MDF/Myna/tree/main/myna/application/additivefoam)
  - [solidification_region_stl](https://github.com/ORNL-MDF/Myna/tree/main/myna/application/additivefoam/solidification_region_stl)
  - [temperature_final_part_stl](https://github.com/ORNL-MDF/Myna/tree/main/myna/application/additivefoam/temperature_final_part_stl)
  - [solidification_region_reduced](https://github.com/ORNL-MDF/Myna/tree/main/myna/application/additivefoam/solidification_region_reduced)
