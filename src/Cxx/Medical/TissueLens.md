### Description
This example uses two vtkClipDataSet filters to achieve a "tissue lens" affect. First, a sphere implicit function is used to clip a spherical hole in the extracted isosurface. Then a geometric sphere samples the original volume data using a vtkProbeFilter. The resulting scalar point data is used to clip the sphere surface with the isosurface value.
