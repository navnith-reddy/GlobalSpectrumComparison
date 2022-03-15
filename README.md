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

The data in this repository has been processed to meet certain criteria outlined in the notebooks. The raw data has been obtained from each nations spectrum planning agency website and has been processed using the pandas software library. The notebooks contained in this repository will not compile without source data which have been excluded from the repository.

> In order to compile notebooks on local machines, users must acquire source datasets independently. Further instructions are provided in each notebook regarding the process.

## Data Visualisation

Frequency allocations have been represented in interactive treemaps. The treemaps were created using the plotly software library. Treemaps are an effective way to represent hierarchical data and may allow the visualisation of spectrum utilisation as well as licence locations.

## Issues with Datasets

The WTR, RLL and UK Spectrum map datasets are imperfect and limit the possibilities of data processing. The WTR is missing many spectrum licences for WBA. The RRL has licence information for very specific geographic locations detailed by HCIS identifiers which results in location specific spectrum utilisation. Any attempt of generalising the information results in practically useless treemaps. The UK spectrum map dataset contains overlapping licences primarily due to shared access allocations, resulting in greater than 100% of certain sections of spectrum. While the technical specifications of Shared Access don't imply interference, the resulting dataset would suggest otherwise.

## Compile Notes

In order compile the notebooks in this repository, you will require python3 and must install the following packages:

- numpy
- plotly
- plotly-express
- pandas
