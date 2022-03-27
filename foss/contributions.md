# Contributions to Free and Open Source Software

## Apache Ozone

* Open Key Cleanup Service
  * [HDDS-6216](https://issues.apache.org/jira/browse/HDDS-6216). Move OMOpenKeysDeleteRequest to package om.request.key
  * [HDDS-5867](https://issues.apache.org/jira/browse/HDDS-5867). Update quota when deleting open keys
  * [HDDS-6228](https://issues.apache.org/jira/browse/HDDS-6228). Update config keys for open key cleanup service
* Erasure Coding
  * [HDDS-6194](https://issues.apache.org/jira/browse/HDDS-6194). EC: Freon ockg support EC write
  * [HDDS-6294](https://issues.apache.org/jira/browse/HDDS-6294). EC: Make cluster-wide EC configuration take effect
  * [HDDS-6347](https://issues.apache.org/jira/browse/HDDS-6347). EC: Freon randomKeys EC key support
  * [HDDS-6232](https://issues.apache.org/jira/browse/HDDS-6232). EC: Update help strings for replication config
  * [HDDS-6358](https://issues.apache.org/jira/browse/HDDS-6358). EC: Refactor ECKeyOutputStream#write()
  * [HDDS-6372](https://issues.apache.org/jira/browse/HDDS-6372). EC: Do not throw NotImplementedException in flush()
  * [HDDS-6452](https://issues.apache.org/jira/browse/HDDS-6372). EC: Fix number of preAllocatedBlocks for EC keys
  * [HDDS-6459](https://issues.apache.org/jira/browse/HDDS-6459). EC: Check isFullCell inside handleDataWrite
* File System Optimization
  * [HDDS-6431](https://issues.apache.org/jira/browse/HDDS-6431). Fix usedBytes for FSO bucket
  * [HDDS-6450](https://issues.apache.org/jira/browse/HDDS-6450). [FSO] Fix correctedSpace for usedBytes in commitKey
* Ozone Streaming
  * [HDDS-5452](https://issues.apache.org/jira/browse/HDDS-5452). Add link() method to ContainerStateMachine
  * [HDDS-5481](https://issues.apache.org/jira/browse/HDDS-5481). Fix stream() and link() method in ContainerStateMachine
  * [HDDS-5488](https://issues.apache.org/jira/browse/HDDS-5488). Add a new BlockOutputStream/KeyOutputStream to support streaming api
  * [HDDS-5705](https://issues.apache.org/jira/browse/HDDS-5705). Change ByteBufStreamOutput to ByteBufferStreamOutput
* Misc
  * [HDDS-6329](https://issues.apache.org/jira/browse/HDDS-6329). New checkstyle: AvoidStarImport
  * [HDDS-6376](https://issues.apache.org/jira/browse/HDDS-6376). Docs: Fix classpath for ofs and o3fs
  * [HDDS-6470](https://issues.apache.org/jira/browse/HDDS-6470). Fix TestOzoneManagerHAWithData#testOMRestart()
  * [HDDS-6480](https://issues.apache.org/jira/browse/HDDS-6480). Add missing CleanupTableInfo to OM responses
  * [HDDS-6509](https://issues.apache.org/jira/browse/HDDS-6509). Checkstyle: Enable setterCanReturnItsClass in HiddenField


## Alluxio

* [#13748](https://github.com/Alluxio/alluxio/pull/13748). Fix integer overflow in usedPercentage
