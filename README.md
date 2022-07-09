- 👋 Hi, I’m @nimiqamin
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
nimiqamin/nimiqamin is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
{
    /**************************NOTICE**************************/
    /*** Following options are NOT active by default. ***/
    /*** You need to uncomment them first by removing the // at the beginning. ***/
    /**************************NOTICE**************************/
/*** Nimiq address to register on the pool ***/
    "address": "NQ50 QHRF 0RT9 9YSM RV4E TX3A JNVQ HYEG SSXK",
/*** Device name. The pool may or may not support this ***/
    "name": "rig1",
/*** Pool servers to connect to ***/
    "server": ['nimiq.icemining.ca'],
/*** Pool ports to connect to ***/
    "port": [2053],
/*** Mining mode: dumb or nano. Notice that Dumb protocol is only supported on some pools. ***/
    "mode": 'dumb',
/*** Array of active devices. eg: [0, 2, 3] ***/
    /*** Default: All available devices. Delete or comment to switch to default. ***/
    //"devices": [0, 2, 3],
/*** Number or an array of active threads per device. eg: 2 or [2, 2, 1] ***/
    /*** Default: 1 ***/
    "threads": 2,
/*** Number or an array of batchsize per thread. eg: 120 or [100, 150, 120] ***/
    /*** Default: Auto based on available device memory. Delete or comment to switch to default. **/
    //"batchsize": 93,
/*** Start difficulty (must be supported on the pool side too) ***/
    //"difficulty": 32,
}
