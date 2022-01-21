cmake_minimum_required(VERSION 3.13.4)

project(SlicerEducation)

#-----------------------------------------------------------------------------
# Extension meta-information
set(EXTENSION_HOMEPAGE "https://www.slicer.org/wiki/Documentation/Nightly/Extensions/SlicerEducation")
set(EXTENSION_CATEGORY "SlicerEducation")
set(EXTENSION_CONTRIBUTORS "Rebecca Hisey (PerkLab, Queens University, Kingston, ON, Canada), David Garcia-Mato (Ebatinca S.L, Las Palmas de Gran Canaria, Spain), Csaba Pinter (Ebatinca S.L, Las Palmas de Gran Canaria, Spain)")
set(EXTENSION_DESCRIPTION "Extension containing modules that enable the creation of educational activities in 3D Slicer.")
set(EXTENSION_ICONURL "http://www.example.com/Slicer/Extensions/SlicerEducation.png")
set(EXTENSION_SCREENSHOTURLS "http://www.example.com/Slicer/Extensions/SlicerEducation/Screenshots/1.png")
set(EXTENSION_DEPENDS "NA") # Specified as a list or "NA" if no dependencies

#-----------------------------------------------------------------------------
# Extension dependencies
find_package(Slicer REQUIRED)
include(${Slicer_USE_FILE})

#-----------------------------------------------------------------------------
# Extension modules
## NEXT_MODULE

#-----------------------------------------------------------------------------
include(${Slicer_EXTENSION_GENERATE_CONFIG})
include(${Slicer_EXTENSION_CPACK})
