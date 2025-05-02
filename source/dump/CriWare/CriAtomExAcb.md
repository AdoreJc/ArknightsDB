# CriAtomExAcb

**Namespace:** `CriWare`


## Fields

- `IntPtr handle`

- `GCHandle dataHandle`


## Properties

- `IntPtr nativeHandle`

- `Boolean isAvailable`


## Methods

- `IntPtr get_nativeHandle()`

- `Boolean get_isAvailable()`

- `Void Dispose(Boolean)`

- `Boolean Exists(String)`

- `Boolean Exists(Int32)`

- `Boolean GetCueInfo(String, out)`

- `Boolean GetCueInfo(Int32, out)`

- `Boolean GetCueInfoByIndex(Int32, out)`

- `Boolean GetWaveFormInfo(String, out)`

- `Boolean GetWaveFormInfo(Int32, out)`

- `Int32 GetNumCuePlaying(String)`

- `Int32 GetNumCuePlaying(Int32)`

- `Int32 GetBlockIndex(String, String)`

- `Int32 GetBlockIndex(Int32, String)`

- `Int32 GetNumUsableAisacControls(String)`

- `Int32 GetNumUsableAisacControls(Int32)`

- `Boolean GetUsableAisacControl(String, Int32, out)`

- `Boolean GetUsableAisacControl(Int32, Int32, out)`

- `Void ResetCueTypeState(String)`

- `Void ResetCueTypeState(Int32)`

- `Void AttachAwbFile(CriFsBinder, String, String)`

- `Void DetachAwbFile(String)`

- `Boolean IsReadyToRelease()`

- `Boolean IsAttachedAwbFile(String)`

- `Single GetLoadProgress()`

- `Void Decrypt(UInt64, UInt64)`


## Dump
```C#
// Dll : CriMw.CriWare.Runtime.dll
// Namespace : CriWare
public class CriAtomExAcb : CriDisposable
{
	private IntPtr handle; // 0x20
	private GCHandle dataHandle; // 0x28

	public IntPtr nativeHandle { get; }
	public Boolean isAvailable { get; }

	// RVA: 0x412336c VA: 0x759673b36c
	public IntPtr get_nativeHandle() { }
	// RVA: 0x4123374 VA: 0x759673b374
	public Boolean get_isAvailable() { }
	// RVA: 0x410f62c VA: 0x759672762c
	public static CriAtomExAcb LoadAcbFile(CriFsBinder binder, String acbPath, String awbPath) { }
	// RVA: 0x410f734 VA: 0x7596727734
	public static CriAtomExAcb LoadAcbData(Byte[] acbData, CriFsBinder awbBinder, String awbPath) { }
	// RVA: 0x4123664 VA: 0x759673b664
	public static CriAtomExAcb LoadAcbData(IntPtr acbData, Int32 dataSize, CriFsBinder awbBinder, String awbPath) { }
	// RVA: 0x4123770 VA: 0x759673b770
	public override Void Dispose() { }
	// RVA: 0x41237d4 VA: 0x759673b7d4
	private Void Dispose(Boolean disposing) { }
	// RVA: 0x4123920 VA: 0x759673b920
	public Boolean Exists(String cueName) { }
	// RVA: 0x41239cc VA: 0x759673b9cc
	public Boolean Exists(Int32 cueId) { }
	// RVA: 0x4123a60 VA: 0x759673ba60
	public Boolean GetCueInfo(String cueName, out CueInfo info) { }
	// RVA: 0x4123d50 VA: 0x759673bd50
	public Boolean GetCueInfo(Int32 cueId, out CueInfo info) { }
	// RVA: 0x4124028 VA: 0x759673c028
	public Boolean GetCueInfoByIndex(Int32 index, out CueInfo info) { }
	// RVA: 0x4124300 VA: 0x759673c300
	public CueInfo[] GetCueInfoList() { }
	// RVA: 0x4124434 VA: 0x759673c434
	public Boolean GetWaveFormInfo(String cueName, out WaveformInfo info) { }
	// RVA: 0x412471c VA: 0x759673c71c
	public Boolean GetWaveFormInfo(Int32 cueId, out WaveformInfo info) { }
	// RVA: 0x41249ec VA: 0x759673c9ec
	public Int32 GetNumCuePlaying(String name) { }
	// RVA: 0x4124a94 VA: 0x759673ca94
	public Int32 GetNumCuePlaying(Int32 id) { }
	// RVA: 0x4124b20 VA: 0x759673cb20
	public Int32 GetBlockIndex(String cueName, String blockName) { }
	// RVA: 0x4124bec VA: 0x759673cbec
	public Int32 GetBlockIndex(Int32 cueId, String blockName) { }
	// RVA: 0x4124ca4 VA: 0x759673cca4
	public Int32 GetNumUsableAisacControls(String cueName) { }
	// RVA: 0x4124d4c VA: 0x759673cd4c
	public Int32 GetNumUsableAisacControls(Int32 cueId) { }
	// RVA: 0x4124dd8 VA: 0x759673cdd8
	public Boolean GetUsableAisacControl(String cueName, Int32 index, out AisacControlInfo info) { }
	// RVA: 0x41250c0 VA: 0x759673d0c0
	public Boolean GetUsableAisacControl(Int32 cueId, Int32 index, out AisacControlInfo info) { }
	// RVA: 0x4125390 VA: 0x759673d390
	public AisacControlInfo[] GetUsableAisacControlList(String cueName) { }
	// RVA: 0x412545c VA: 0x759673d45c
	public AisacControlInfo[] GetUsableAisacControlList(Int32 cueId) { }
	// RVA: 0x4125528 VA: 0x759673d528
	public Void ResetCueTypeState(String cueName) { }
	// RVA: 0x41255c8 VA: 0x759673d5c8
	public Void ResetCueTypeState(Int32 cueId) { }
	// RVA: 0x4125654 VA: 0x759673d654
	public Void AttachAwbFile(CriFsBinder awb_binder, String awb_path, String awb_name) { }
	// RVA: 0x41257d8 VA: 0x759673d7d8
	public Void DetachAwbFile(String awb_name) { }
	// RVA: 0x41258a8 VA: 0x759673d8a8
	public Boolean IsReadyToRelease() { }
	// RVA: 0x4125954 VA: 0x759673d954
	public Boolean IsAttachedAwbFile(String awbName) { }
	// RVA: 0x4125a34 VA: 0x759673da34
	public Single GetLoadProgress() { }
	// RVA: 0x4125a3c VA: 0x759673da3c
	public Void Decrypt(UInt64 key, UInt64 nonce) { }
	// RVA: 0x41234ac VA: 0x759673b4ac
	internal Void .ctor(IntPtr handle, Nullable`1 dataHandle) { }
	// RVA: 0x4125ab4 VA: 0x759673dab4
	protected override Void Finalize() { }
	// RVA: 0x41233c8 VA: 0x759673b3c8
	private static extern IntPtr criAtomExAcb_LoadAcbFile(IntPtr acb_binder, String acb_path, IntPtr awb_binder, String awb_path, IntPtr work, Int32 work_size) { }
	// RVA: 0x4123594 VA: 0x759673b594
	private static extern IntPtr criAtomExAcb_LoadAcbData(IntPtr acb_data, Int32 acb_data_size, IntPtr awb_binder, String awb_path, IntPtr work, Int32 work_size) { }
	// RVA: 0x41238a4 VA: 0x759673b8a4
	private static extern Void criAtomExAcb_Release(IntPtr acb_hn) { }
	// RVA: 0x41243b8 VA: 0x759673c3b8
	private static extern Int32 criAtomExAcb_GetNumCues(IntPtr acb_hn) { }
	// RVA: 0x41239d4 VA: 0x759673b9d4
	private static extern Boolean criAtomExAcb_ExistsId(IntPtr acb_hn, Int32 id) { }
	// RVA: 0x4123928 VA: 0x759673b928
	private static extern Boolean criAtomExAcb_ExistsName(IntPtr acb_hn, String name) { }
	// RVA: 0x4124d54 VA: 0x759673cd54
	private static extern Int32 criAtomExAcb_GetNumUsableAisacControlsById(IntPtr acb_hn, Int32 id) { }
	// RVA: 0x4124cac VA: 0x759673ccac
	private static extern Int32 criAtomExAcb_GetNumUsableAisacControlsByName(IntPtr acb_hn, String name) { }
	// RVA: 0x41252ec VA: 0x759673d2ec
	private static extern Boolean criAtomExAcb_GetUsableAisacControlById(IntPtr acb_hn, Int32 id, UInt16 index, IntPtr info) { }
	// RVA: 0x4125004 VA: 0x759673d004
	private static extern Boolean criAtomExAcb_GetUsableAisacControlByName(IntPtr acb_hn, String name, UInt16 index, IntPtr info) { }
	// RVA: 0x4124950 VA: 0x759673c950
	private static extern Boolean criAtomExAcb_GetWaveformInfoById(IntPtr acb_hn, Int32 id, IntPtr waveform_info) { }
	// RVA: 0x4124668 VA: 0x759673c668
	private static extern Boolean criAtomExAcb_GetWaveformInfoByName(IntPtr acb_hn, String name, IntPtr waveform_info) { }
	// RVA: 0x4123c9c VA: 0x759673bc9c
	private static extern Boolean criAtomExAcb_GetCueInfoByName(IntPtr acb_hn, String name, IntPtr info) { }
	// RVA: 0x4123f8c VA: 0x759673bf8c
	private static extern Boolean criAtomExAcb_GetCueInfoById(IntPtr acb_hn, Int32 id, IntPtr info) { }
	// RVA: 0x4124264 VA: 0x759673c264
	private static extern Boolean criAtomExAcb_GetCueInfoByIndex(IntPtr acb_hn, Int32 index, IntPtr info) { }
	// RVA: 0x41249f4 VA: 0x759673c9f4
	private static extern Int32 criAtomExAcb_GetNumCuePlayingCountByName(IntPtr acb_hn, String name) { }
	// RVA: 0x4124a9c VA: 0x759673ca9c
	private static extern Int32 criAtomExAcb_GetNumCuePlayingCountById(IntPtr acb_hn, Int32 id) { }
	// RVA: 0x4124bf4 VA: 0x759673cbf4
	private static extern Int32 criAtomExAcb_GetBlockIndexById(IntPtr acb_hn, Int32 id, String block_name) { }
	// RVA: 0x4124b28 VA: 0x759673cb28
	private static extern Int32 criAtomExAcb_GetBlockIndexByName(IntPtr acb_hn, String name, String block_name) { }
	// RVA: 0x4125530 VA: 0x759673d530
	private static extern Void criAtomExAcb_ResetCueTypeStateByName(IntPtr acb_hn, String name) { }
	// RVA: 0x41255d0 VA: 0x759673d5d0
	private static extern Void criAtomExAcb_ResetCueTypeStateById(IntPtr acb_hn, Int32 id) { }
	// RVA: 0x41256fc VA: 0x759673d6fc
	private static extern Void criAtomExAcb_AttachAwbFile(IntPtr acb_hn, IntPtr awb_binder, String awb_path, String awb_name, IntPtr work, Int32 work_size) { }
	// RVA: 0x4125810 VA: 0x759673d810
	private static extern Void criAtomExAcb_DetachAwbFile(IntPtr acb_hn, String awb_name) { }
	// RVA: 0x41258d0 VA: 0x759673d8d0
	private static extern Boolean criAtomExAcb_IsReadyToRelease(IntPtr acb_hn) { }
	// RVA: 0x4125990 VA: 0x759673d990
	private static extern Boolean criAtomExAcb_IsAttachedAwbFile(IntPtr acbHn, String awbName) { }
}
```