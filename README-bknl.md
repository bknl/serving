These are extensions to the stock TensorFlow Serving model servers to add:

- secure channel gRPC               (branch sslserver)
- dynamically loadable operators    (branch loadlibrary)

These are intended to make the server play nicely with the SAP HANA Database
(see: https://help.sap.com/viewer/p/SAP_HANA_PLATFORM).

In addition, for each release of the SAP HANA External Machine Library
(see https://help.sap.com/viewer/ab6b04eb12d3452aa904d5823416a065/2.0.02/en-US/abfc6b11fc3e41e98408df593a06ad16.html)
there will be a branch corresponding to model servers published together with that release, starting with HANA 2.0 SPS03.

You can find RPMs with prebuilt binaries for the platforms supported by SAP HANA at

    https://drive.google.com/drive/folders/0B_HaefMdDVd8QXZkY2tIcFpuUVU

Note that neither the binaries nor the source code are officially supported by SAP.
