# UnityAudioEngine

**Namespace:** `Torappu.Audio.Engine.Unity`


## Fields

- `AudioClipManager m_clipManager`

- `AudioOptions m_audioOptions`

- `IEnumerator m_snapshotDelay`


## Methods

- `AudioMixerGroup GetMixerByDesc(MixerDesc)`

- `IEnumerator _TransitionToSnapshotDelayRoutine(AudioMixerSnapshot[], Single[], Single, Single)`

- `AudioMixerSnapshot _FindSnapshot(String)`

- `Void <>xLuaBaseProxy_OnInit()`

- `Void <>xLuaBaseProxy_OnReloadBanks()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Audio.Engine.Unity
public class UnityAudioEngine : AudioEngine
{
	private AudioClipManager m_clipManager; // 0x38
	private AudioOptions m_audioOptions; // 0x40
	private Dictionary`2 m_findGroupCache; // 0x48
	private ListDict`2 m_findSnapshotCache; // 0x50
	private IEnumerator m_snapshotDelay; // 0x58
	private AudioMixerSnapshot[] m_singleSnapshot; // 0x60
	private static DelegateBridge __Hotfix0_get_engineType; // 0x0
	private static DelegateBridge __Hotfix0_get_assetMgr; // 0x8
	private static DelegateBridge __Hotfix0_CreatePlayback; // 0x10
	private static DelegateBridge __Hotfix0_SetMixerParamImpl; // 0x18
	private static DelegateBridge __Hotfix0_GetMixerParamImpl; // 0x20
	private static DelegateBridge __Hotfix0_CreateAudioListener; // 0x28
	private static DelegateBridge __Hotfix0_OnInit; // 0x30
	private static DelegateBridge __Hotfix0_OnReloadBanks; // 0x38
	private static DelegateBridge __Hotfix0_GetMixerByDesc; // 0x40
	private static DelegateBridge __Hotfix0_TransitionToSnapshot; // 0x48
	private static DelegateBridge __Hotfix0__TransitionToSnapshotDelayRoutine; // 0x50
	private static DelegateBridge __Hotfix0__FindSnapshot; // 0x58
	private static DelegateBridge _c__Hotfix0_ctor; // 0x60

	public override AudioEngineType engineType { get; }
	public override AudioAssetManager assetMgr { get; }

	// RVA: 0x3ee5608 VA: 0x75964fd608
	public override AudioEngineType get_engineType() { }
	// RVA: 0x3ee566c VA: 0x75964fd66c
	public override AudioAssetManager get_assetMgr() { }
	// RVA: 0x3ee56d4 VA: 0x75964fd6d4
	public override AudioPlayback CreatePlayback() { }
	// RVA: 0x3ee5814 VA: 0x75964fd814
	protected override Void SetMixerParamImpl(String name, Single value) { }
	// RVA: 0x3ee58c4 VA: 0x75964fd8c4
	protected override Boolean GetMixerParamImpl(String name, out Single value) { }
	// RVA: 0x3ee5968 VA: 0x75964fd968
	public override Component CreateAudioListener(GameObject listenerObj) { }
	// RVA: 0x3ee5a04 VA: 0x75964fda04
	protected override Void OnInit() { }
	// RVA: 0x3ee5aec VA: 0x75964fdaec
	protected override Void OnReloadBanks() { }
	// RVA: 0x3ee5bc8 VA: 0x75964fdbc8
	public AudioMixerGroup GetMixerByDesc(MixerDesc desc) { }
	// RVA: 0x3ee5e20 VA: 0x75964fde20
	public override Boolean TransitionToSnapshot(SnapshotTransition transition) { }
	// RVA: 0x3ee6324 VA: 0x75964fe324
	private IEnumerator _TransitionToSnapshotDelayRoutine(AudioMixerSnapshot[] snapshots, Single[] weights, Single duration, Single delay) { }
	// RVA: 0x3ee61c8 VA: 0x75964fe1c8
	private AudioMixerSnapshot _FindSnapshot(String name) { }
	// RVA: 0x3ee6458 VA: 0x75964fe458
	public Void .ctor() { }
	// RVA: 0x3ee656c VA: 0x75964fe56c
	private Void <>xLuaBaseProxy_OnInit() { }
	// RVA: 0x3ee6574 VA: 0x75964fe574
	private Void <>xLuaBaseProxy_OnReloadBanks() { }
}
```