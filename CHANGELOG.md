# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## Unreleased

### Added

### Changed

### Removed


## [0.10.0] 2025-02-03

### Added

### Changed

* Changed default node size, node color, and edge color of graph object.
* Changed default vertex size, vertex color, edge color, and face color of mesh object.

### Removed


## [0.9.0] 2025-02-01

### Added

* Added `compas_notebook.conversions.shapes_to_edgesbuffer`.
* Added `compas_notebook.conversions.shapes_to_facesbuffer`.
* Added `compas_notebook.scene.ThreeGroupObject`.

### Changed

### Removed


## [0.8.2] 2025-01-31

### Added

### Changed

* Fixed bug in intialisation of orbit controls.
* Changed `compas_notebook.config.CameraConfig.position` to have a default of `[0, -10, 5]`.

### Removed


## [0.8.1] 2024-08-25

### Added

### Changed

* Changed registration of scene objects to not print messages.

### Removed


## [0.8.0] 2024-08-23

### Added

### Changed

* Changed `compas_notebook.scene.ThreeBrepObject` to be compatible with `compas>=2.4`.
* Changed `compas_notebook.scene.ThreeMeshObject` to be compatible with `compas>=2.4`.

### Removed


## [0.7.0] 2024-08-23

### Added

* Added custom scene `compas_notebook.scene.Scene`.
* Added default base color to all scene objects.

### Changed

### Removed

* Removed `scene=None` parameter from viewer constructor.


## [0.6.1] 2024-05-12

### Added

### Changed

* Fixed broken import `from compas.utilities import pairwise`.
* Changed viewer initalisation to use default config object and not config from json.
* Changed `compas_notebook.config.SidebarConfig.show` to `False`.

### Removed

* Removed `load_scene` and `save_scene` from default toolbar.


## [0.6.0] 2024-04-17

### Added

### Changed

* Fixed `ValueError` when starting viewer for the first time with default config.

### Removed


## [0.5.0] 2024-03-08

### Added

### Changed

### Removed


## [0.4.0] 2024-03-08

### Added

* Added `compas_notebook.config.Config`.
* Added `compas_notebook.controller.Controller`.
* Added support for sidebar with configurable widgets and actions.
* Added base configuration file: `compas_notebook/config.json`.

### Changed

* Changed repo config to `pyproject.toml`.

### Removed


## [0.3.4] 2024-02-09

### Added

### Changed

### Removed


## [0.2.1] 2024-02-09

### Added

### Changed

### Removed


## [0.2.0] 2024-02-08

### Added

* Added support for `compas_notebook.scene.ThreeMeshObject.vertexcolor`.
* Added support for `compas_notebook.scene.ThreeMeshObject.edgecolor`.
* Added support for `compas_notebook.scene.ThreeMeshObject.facecolor`.
* Added support for Ngon faces.

### Changed

* Changed name of all scene objects to use prefix `Three`.

### Removed


## [0.1.5] 2024-02-06

### Added

* Added `compas_notebook.scene.PointObject`.
* Added `compas_notebook.scene.PointcloudObject`.
* Added `compas_notebook.scene.PolylineObject`.
* Added `compas_notebook.scene.LineObject`.
* Added `compas_notebook.scene.GraphObject`.

### Changed

### Removed

## [0.1.4] 2024-02-05

### Added

* Added `compas_notebook.scene.PolygonObject`.
* Added `compas_notebook.viewer.Viewer.update`.
* Added `compas_notebook.scene.CapsuleObject`.
* Added `compas_notebook.scene.PolygonObject`.

### Changed

* Fixed `compas_notebook.viewer.Viewer.zoom_in`.
* Fixed `compas_notebook.viewer.Viewer.zoom_out`.

### Removed


## [0.1.3] 2024-02-02

### Added

* Added `compas_notebook.scene.BrepObject`.
* Added `compas_notebook.conversions.polyline_to_threejs`.

### Changed

### Removed


## [0.1.2] 2024-01-31

### Added

### Changed

### Removed


## [0.1.1] 2024-01-31

### Added

* Added `compas_notebook.conversions.color_to_threejs`.
* Added `compas_notebook.conversions.box_to_threejs`.
* Added `compas_notebook.conversions.cone_to_threejs`.
* Added `compas_notebook.conversions.cylinder_to_threejs`.
* Added `compas_notebook.conversions.polyhedron_to_threejs`.
* Added `compas_notebook.conversions.sphere_to_threejs`.
* Added `compas_notebook.conversions.torus_to_threejs`.
* Added `compas_notebook.scene.BoxObject`.
* Added `compas_notebook.scene.ConeObject`.
* Added `compas_notebook.scene.CylinderObject`.
* Added `compas_notebook.scene.MeshObject`.
* Added `compas_notebook.scene.PolyhedronObject`.
* Added `compas_notebook.scene.SphereObject`.
* Added `compas_notebook.scene.TorusObject`.
* Added `compas_notebook.viewer.Viewer`.

### Changed

### Removed
