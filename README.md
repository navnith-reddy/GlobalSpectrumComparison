# Global Spectrum Comparison

Spectrum management is a collaborative process and often requires cooperation between various spectrum planning agencies worldwide. When implementing new changes to radiocommunication policy, it is often useful to cite the frequency allocations of other nations, however, the process of analysing international spectrum usage is not straightforward or convenient. 

The notebooks in the repository aim to address this issue by creating interactive data representations of individual nations spectrum allocations. The focus of the project will be on mid-band wireless broadband access utilisation of spectrum.

The project contains spectrum licence data from the following countries:
- Australia
- UK

Countries yet to be included:
- New Zealand
- Canada
- USA

Spectrum licencing practices vary between nations, especially in regards to the distribution of geographical areas with reference to frequency allocations. A challenge associated with visualising frequency allocation data is to accurately convey spectrum usage AND location.

## Data Processing

The data in this repository has been processed to meet certain criteria outlined in the notebooks. The raw data has been obtained from each nations spectrum planning agency website and has been processed using the pandas software library.

## Data Visualisation

Frequency allocations have been represented in interactive treemaps. The treemaps were created using the plotly software library. Treemaps are an effective way to represent hierarchical data and may allow the visualisation of spectrum utilisation as well as licence locations.