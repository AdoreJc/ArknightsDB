# CriAtom

**Namespace:** `CriWare`


## Fields

- `String acfFile`

- `Boolean acfIsLoading`

- `String dspBusSetting`

- `Boolean dontDestroyOnLoad`

- `GCHandle acfRegisterGCHandle`

- `Boolean dontRemoveExistsCueSheet`


## Methods

- `Void Setup()`

- `Void Shutdown()`

- `Void Awake()`

- `Void OnDestroy()`

- `CriAtomCueSheet GetCueSheetInternal(String)`

- `CriAtomCueSheet AddCueSheetInternal(String, String, String, CriFsBinder)`

- `Void RemoveCueSheetInternal(String)`

- `Void MargeCueSheet(CriAtomCueSheet[], Boolean)`

- `CriAtomExAcb LoadAcbFile(CriFsBinder, String, String)`

- `CriAtomExAcb LoadAcbData(Byte[], CriFsBinder, String)`

- `Void LoadAcbFileAsync(CriAtomCueSheet, CriFsBinder, String, String, Boolean)`

- `IEnumerator LoadAcbFileCoroutine(CriAtomCueSheet, CriFsBinder, String, String, Boolean)`

- `Void LoadAcbDataAsync(CriAtomCueSheet, Byte[], CriFsBinder, String, Boolean)`

- `IEnumerator LoadAcbDataCoroutine(CriAtomCueSheet, Byte[], CriFsBinder, String, Boolean)`


## Dump
```C#
// Dll : CriMw.CriWare.Runtime.dll
// Namespace : CriWare
public class CriAtom : CriMonoBehaviour
{
	public String acfFile; // 0x28
	private Boolean acfIsLoading; // 0x30
	public CriAtomCueSheet[] cueSheets; // 0x38
	public String dspBusSetting; // 0x40
	public Boolean dontDestroyOnLoad; // 0x48
	private static EventCallback eventUserCallback; // 0x0
	private static EventCbFunc eventUserCbFunc; // 0x8
	private static CbFunc beatsyncUserCbFunc; // 0x10
	private static CbFunc obsoleteBeatSyncFunc; // 0x18
	private static CueLinkCbFunc cueLinkUserCbFunc; // 0x20
	private static CriAtom <instance>k__BackingField; // 0x28
	private GCHandle acfRegisterGCHandle; // 0x50
	public Boolean dontRemoveExistsCueSheet; // 0x58

	internal static Boolean HasUserCallback { get; }
	internal static Boolean HasBeatSyncCallback { get; }
	internal static Boolean HasCueLinkCallback { get; }
	private static CriAtom instance { get; set; }
	public static Boolean CueSheetsAreLoading { get; }

	// RVA: 0x410c338 VA: 0x7596724338
	public static Int32 GetThreadPriorityANDROID() { }
	// RVA: 0x410c3a4 VA: 0x75967243a4
	public static Void SetThreadPriorityANDROID(Int32 prio) { }
	// RVA: 0x410c424 VA: 0x7596724424
	internal static Boolean get_HasUserCallback() { }
	// RVA: 0x410c474 VA: 0x7596724474
	internal static Void add_OnEventSequencerCallback(EventCallback value) { }
	// RVA: 0x410c608 VA: 0x7596724608
	internal static Void remove_OnEventSequencerCallback(EventCallback value) { }
	// RVA: 0x410c72c VA: 0x759672472c
	private static Void add_beatsyncUserCbFunc(CbFunc value) { }
	// RVA: 0x410c7e8 VA: 0x75967247e8
	private static Void remove_beatsyncUserCbFunc(CbFunc value) { }
	// RVA: 0x410c8a4 VA: 0x75967248a4
	internal static Boolean get_HasBeatSyncCallback() { }
	// RVA: 0x410c8f4 VA: 0x75967248f4
	internal static Void add_OnBeatSyncCallback(CbFunc value) { }
	// RVA: 0x410ca14 VA: 0x7596724a14
	internal static Void remove_OnBeatSyncCallback(CbFunc value) { }
	// RVA: 0x410cac4 VA: 0x7596724ac4
	private static Void add_cueLinkUserCbFunc(CueLinkCbFunc value) { }
	// RVA: 0x410cb80 VA: 0x7596724b80
	private static Void remove_cueLinkUserCbFunc(CueLinkCbFunc value) { }
	// RVA: 0x410cc3c VA: 0x7596724c3c
	internal static Boolean get_HasCueLinkCallback() { }
	// RVA: 0x410cc8c VA: 0x7596724c8c
	internal static Void add_OnCueLinkCallback(CueLinkCbFunc value) { }
	// RVA: 0x410cdac VA: 0x7596724dac
	internal static Void remove_OnCueLinkCallback(CueLinkCbFunc value) { }
	// RVA: 0x410ce5c VA: 0x7596724e5c
	private static CriAtom get_instance() { }
	// RVA: 0x410cea4 VA: 0x7596724ea4
	private static Void set_instance(CriAtom value) { }
	// RVA: 0x410cef4 VA: 0x7596724ef4
	public static Void AttachDspBusSetting(String settingName) { }
	// RVA: 0x410d088 VA: 0x7596725088
	public static Void DetachDspBusSetting() { }
	// RVA: 0x410d128 VA: 0x7596725128
	public static CriAtomCueSheet GetCueSheet(String name) { }
	// RVA: 0x410d200 VA: 0x7596725200
	public static CriAtomCueSheet AddCueSheet(String name, String acbFile, String awbFile, CriFsBinder binder) { }
	// RVA: 0x410d5a4 VA: 0x75967255a4
	public static CriAtomCueSheet AddCueSheetAsync(String name, String acbFile, String awbFile, CriFsBinder binder, Boolean loadAwbOnMemory) { }
	// RVA: 0x410d708 VA: 0x7596725708
	public static CriAtomCueSheet AddCueSheet(String name, Byte[] acbData, String awbFile, CriFsBinder awbBinder) { }
	// RVA: 0x410d8e0 VA: 0x75967258e0
	public static CriAtomCueSheet AddCueSheetAsync(String name, Byte[] acbData, String awbFile, CriFsBinder awbBinder, Boolean loadAwbOnMemory) { }
	// RVA: 0x410da1c VA: 0x7596725a1c
	public static Void RemoveCueSheet(String name) { }
	// RVA: 0x410dc64 VA: 0x7596725c64
	public static Boolean get_CueSheetsAreLoading() { }
	// RVA: 0x410dd80 VA: 0x7596725d80
	public static CriAtomExAcb GetAcb(String cueSheetName) { }
	// RVA: 0x410dec4 VA: 0x7596725ec4
	public static Void SetCategoryVolume(String name, Single volume) { }
	// RVA: 0x410decc VA: 0x7596725ecc
	public static Void SetCategoryVolume(Int32 id, Single volume) { }
	// RVA: 0x410ded4 VA: 0x7596725ed4
	public static Single GetCategoryVolume(String name) { }
	// RVA: 0x410dedc VA: 0x7596725edc
	public static Single GetCategoryVolume(Int32 id) { }
	// RVA: 0x410dee4 VA: 0x7596725ee4
	public static Void SetBusAnalyzer(String busName, Boolean sw) { }
	// RVA: 0x410df28 VA: 0x7596725f28
	public static Void SetBusAnalyzer(Boolean sw) { }
	// RVA: 0x410dfd8 VA: 0x7596725fd8
	public static BusAnalyzerInfo GetBusAnalyzerInfo(String busName) { }
	// RVA: 0x410e208 VA: 0x7596726208
	public static BusAnalyzerInfo GetBusAnalyzerInfo(Int32 busId) { }
	// RVA: 0x410e438 VA: 0x7596726438
	public Void Setup() { }
	// RVA: 0x410e770 VA: 0x7596726770
	public Void Shutdown() { }
	// RVA: 0x410eec0 VA: 0x7596726ec0
	private Void Awake() { }
	// RVA: 0x410f304 VA: 0x7596727304
	protected override Void OnEnable() { }
	// RVA: 0x410f3b8 VA: 0x75967273b8
	private Void OnDestroy() { }
	// RVA: 0x410f5a4 VA: 0x75967275a4
	public override Void CriInternalUpdate() { }
	// RVA: 0x410f5a8 VA: 0x75967275a8
	public override Void CriInternalLateUpdate() { }
	// RVA: 0x410d180 VA: 0x7596725180
	public CriAtomCueSheet GetCueSheetInternal(String name) { }
	// RVA: 0x410d2e4 VA: 0x75967252e4
	public CriAtomCueSheet AddCueSheetInternal(String name, String acbFile, String awbFile, CriFsBinder binder) { }
	// RVA: 0x410db00 VA: 0x7596725b00
	public Void RemoveCueSheetInternal(String name) { }
	// RVA: 0x410f124 VA: 0x7596727124
	private Void MargeCueSheet(CriAtomCueSheet[] newCueSheets, Boolean newDontRemoveExistsCueSheet) { }
	// RVA: 0x410d478 VA: 0x7596725478
	private CriAtomExAcb LoadAcbFile(CriFsBinder binder, String acbFile, String awbFile) { }
	// RVA: 0x410d814 VA: 0x7596725814
	private CriAtomExAcb LoadAcbData(Byte[] acbData, CriFsBinder binder, String awbFile) { }
	// RVA: 0x410d680 VA: 0x7596725680
	private Void LoadAcbFileAsync(CriAtomCueSheet cueSheet, CriFsBinder binder, String acbFile, String awbFile, Boolean loadAwbOnMemory) { }
	// RVA: 0x410f890 VA: 0x7596727890
	private IEnumerator LoadAcbFileCoroutine(CriAtomCueSheet cueSheet, CriFsBinder binder, String acbPath, String awbPath, Boolean loadAwbOnMemory) { }
	// RVA: 0x410d9f8 VA: 0x75967259f8
	private Void LoadAcbDataAsync(CriAtomCueSheet cueSheet, Byte[] acbData, CriFsBinder awbBinder, String awbFile, Boolean loadAwbOnMemory) { }
	// RVA: 0x410f9a0 VA: 0x75967279a0
	private IEnumerator LoadAcbDataCoroutine(CriAtomCueSheet cueSheet, Byte[] acbData, CriFsBinder awbBinder, String awbPath, Boolean loadAwbOnMemory) { }
	// RVA: 0x410c188 VA: 0x7596724188
	public static Void SequenceEventCallbackFromNative(String eventString) { }
	// RVA: 0x410c1f4 VA: 0x75967241f4
	private static Void SequenceCallbackFromNative(ref CriAtomExSequenceEventInfo criAtomExSequenceInfo) { }
	// RVA: 0x410c260 VA: 0x7596724260
	public static Void BeatSyncCallbackFromNative(ref Info info) { }
	// RVA: 0x410c2cc VA: 0x75967242cc
	public static Void CueLinkCallbackFromNative(ref CueLinkInfo info) { }
	// RVA: 0x410fab0 VA: 0x7596727ab0
	public static Void SetEventCallback(EventCbFunc func, String separator) { }
	// RVA: 0x410c478 VA: 0x7596724478
	private static Void RegisterEventCallbackChain(EventCallback func) { }
	// RVA: 0x410c60c VA: 0x759672460c
	private static Void UnregisterEventCallbackChain(EventCallback func) { }
	// RVA: 0x410fecc VA: 0x7596727ecc
	public static Void SetBeatSyncCallback(CbFunc func) { }
	// RVA: 0x410c8f8 VA: 0x75967248f8
	private static Void RegisterBeatSyncCallbackChain(CbFunc func) { }
	// RVA: 0x410ca18 VA: 0x7596724a18
	private static Void UnregisterBeatSyncCallbackChain(CbFunc func) { }
	// RVA: 0x410cc90 VA: 0x7596724c90
	private static Void RegisterCueLinkCallbackChain(CueLinkCbFunc func) { }
	// RVA: 0x410cdb0 VA: 0x7596724db0
	private static Void UnregisterCueLinkCallbackChain(CueLinkCbFunc func) { }
	// RVA: 0x41101f4 VA: 0x75967281f4
	public Void .ctor() { }
}
```