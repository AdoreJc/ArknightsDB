# AudioClipManager

**Namespace:** `Torappu.Audio.Engine.Unity`


## Fields

- `AudioClipResPool m_clipPool`


## Methods

- `AudioClip _LoadClip(String, String, Boolean)`

- `Void _UnloadClipByRef(String)`

- `Void _UnloadClips(AudioAssetRefCollection)`

- `Void _UnloadAll()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Audio.Engine.Unity
public class AudioClipManager : AudioAssetManager
{
	private AudioClipResPool m_clipPool; // 0x10
	private List`1 m_tempClips; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0__LoadClip; // 0x8
	private static DelegateBridge __Hotfix0__UnloadClipByRef; // 0x10
	private static DelegateBridge __Hotfix0__FindClipsWithPersistTag; // 0x18
	private static DelegateBridge __Hotfix0__UnloadClips; // 0x20
	private static DelegateBridge __Hotfix0__UnloadAll; // 0x28
	private static DelegateBridge __Hotfix0_LoadSound; // 0x30
	private static DelegateBridge __Hotfix0_LoadMusic; // 0x38
	private static DelegateBridge __Hotfix0_UnloadAssetByRef; // 0x40
	private static DelegateBridge __Hotfix0_FindAssetsByTag; // 0x48
	private static DelegateBridge __Hotfix0_ForceUnloadAssets; // 0x50
	private static DelegateBridge __Hotfix0_OnReloadBanks; // 0x58
	private static DelegateBridge __Hotfix0_Dispose; // 0x60


	// RVA: 0x3ee4338 VA: 0x75964fc338
	public Void .ctor() { }
	// RVA: 0x3ee442c VA: 0x75964fc42c
	private AudioClip _LoadClip(String key, String persistTag, Boolean forceLoadData) { }
	// RVA: 0x3ee44f8 VA: 0x75964fc4f8
	private Void _UnloadClipByRef(String key) { }
	// RVA: 0x3ee4598 VA: 0x75964fc598
	private List`1 _FindClipsWithPersistTag(String persistTag) { }
	// RVA: 0x3ee46a0 VA: 0x75964fc6a0
	private Void _UnloadClips(AudioAssetRefCollection collection) { }
	// RVA: 0x3ee4924 VA: 0x75964fc924
	private Void _UnloadAll() { }
	// RVA: 0x3ee4b1c VA: 0x75964fcb1c
	protected override AudioAsset LoadSound(String name, ISoundInfo info, LoadAssetOptions options) { }
	// RVA: 0x3ee4d10 VA: 0x75964fcd10
	protected override AudioAsset LoadMusic(String name, IMusicInfo info, LoadAssetOptions options) { }
	// RVA: 0x3ee5008 VA: 0x75964fd008
	public override Void UnloadAssetByRef(AudioAsset asset) { }
	// RVA: 0x3ee5118 VA: 0x75964fd118
	public override Void FindAssetsByTag(String persistTag, AudioAssetRefCollection collection) { }
	// RVA: 0x3ee5310 VA: 0x75964fd310
	public override Void ForceUnloadAssets(AudioAssetRefCollection collection) { }
	// RVA: 0x3ee53a4 VA: 0x75964fd3a4
	public override Void OnReloadBanks() { }
	// RVA: 0x3ee540c VA: 0x75964fd40c
	public override Void Dispose() { }
}
```