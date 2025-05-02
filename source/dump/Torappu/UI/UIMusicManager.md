# UIMusicManager

**Namespace:** `Torappu.UI`


## Fields

- `Boolean m_hasPendingMusicChanges`

- `MixerParamMgr m_mixerParamMgr`


## Methods

- `Int32 _BlockMusicChanges(Object)`

- `Void _ReleaseMusicBlocker(Int32)`

- `Boolean _IsMusicChangable()`

- `Boolean _CheckIfToClearMusic()`

- `Void _AddClearMusicChunk(Int32)`

- `Void _RemoveClearMusicChunk(Int32)`

- `Void Dispose()`

- `Void _SyncPlayingMusicImpl()`

- `Void _ApplyEffect(Int64, IMusicEffect)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIMusicManager : SingletonInScene`1, IHotfixable, IDisposable
{
	private static readonly ChunkConfig CLEAR_MUSIC_CHUNK; // 0x0
	private ListDict`2 m_changeBlockers; // 0x18
	private Boolean m_hasPendingMusicChanges; // 0x20
	private ListSet`1 m_clearMusicRequests; // 0x28
	private static Dictionary`2 s_alias2InstanceIdDict; // 0x28
	private static Int64 s_instanceId; // 0x30
	private ListDict`2 m_chunkStack; // 0x30
	private MixerParamMgr m_mixerParamMgr; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38
	private static DelegateBridge __Hotfix0__BlockMusicChanges; // 0x40
	private static DelegateBridge __Hotfix0__ReleaseMusicBlocker; // 0x48
	private static DelegateBridge __Hotfix0__IsMusicChangable; // 0x50
	private static DelegateBridge __Hotfix0__CheckIfToClearMusic; // 0x58
	private static DelegateBridge __Hotfix0_AddClearMusicChunk; // 0x60
	private static DelegateBridge __Hotfix0_RemoveClearMusicChunk; // 0x68
	private static DelegateBridge __Hotfix0__AddClearMusicChunk; // 0x70
	private static DelegateBridge __Hotfix0__RemoveClearMusicChunk; // 0x78
	private static DelegateBridge __Hotfix0_GetInstanceIdByAlias; // 0x80
	private static DelegateBridge __Hotfix0_Dispose; // 0x88
	private static DelegateBridge __Hotfix0_TestMusicSignal; // 0x90
	private static DelegateBridge __Hotfix0_BlockMusicChanges; // 0x98
	private static DelegateBridge __Hotfix0_ReleaseMusicChangeBlocker; // 0xa0
	private static DelegateBridge __Hotfix0_ModifyMusicChunk; // 0xa8
	private static DelegateBridge __Hotfix0_ModifyMusicChunkById; // 0xb0
	private static DelegateBridge __Hotfix0_RemoveMusicChunk; // 0xb8
	private static DelegateBridge __Hotfix0_SyncPlayingMusic; // 0xc0
	private static DelegateBridge __Hotfix0__SyncPlayingMusicImpl; // 0xc8
	private static DelegateBridge __Hotfix0__ApplyEffect; // 0xd0
	private static DelegateBridge __Hotfix0__ConvertToAudioModule; // 0xd8
	private static DelegateBridge __Hotfix0_TryGetMusicParamInfo; // 0xe0


	// RVA: 0x21c9418 VA: 0x75947e1418
	private Void .ctor() { }
	// RVA: 0x21c96c4 VA: 0x75947e16c4
	private Int32 _BlockMusicChanges(Object blockRef) { }
	// RVA: 0x21c9854 VA: 0x75947e1854
	private Void _ReleaseMusicBlocker(Int32 id) { }
	// RVA: 0x21c99e4 VA: 0x75947e19e4
	private Boolean _IsMusicChangable() { }
	// RVA: 0x21c9e58 VA: 0x75947e1e58
	private Boolean _CheckIfToClearMusic() { }
	// RVA: 0x21c9efc VA: 0x75947e1efc
	public static Void AddClearMusicChunk(Int32 instId) { }
	// RVA: 0x21ca048 VA: 0x75947e2048
	public static Void RemoveClearMusicChunk(Int32 instId) { }
	// RVA: 0x21c9f98 VA: 0x75947e1f98
	private Void _AddClearMusicChunk(Int32 instId) { }
	// RVA: 0x21ca0e4 VA: 0x75947e20e4
	private Void _RemoveClearMusicChunk(Int32 instId) { }
	// RVA: 0x21ca194 VA: 0x75947e2194
	public static Int64 GetInstanceIdByAlias(String alias) { }
	// RVA: 0x21ca2c8 VA: 0x75947e22c8
	public Void Dispose() { }
	// RVA: 0x21ca35c VA: 0x75947e235c
	public static Boolean TestMusicSignal(ChunkConfig config) { }
	// RVA: 0x21ca454 VA: 0x75947e2454
	public static Int32 BlockMusicChanges(Object blockRef) { }
	// RVA: 0x21ca4f0 VA: 0x75947e24f0
	public static Void ReleaseMusicChangeBlocker(Int32 id) { }
	// RVA: 0x21ca58c VA: 0x75947e258c
	public static Void ModifyMusicChunk(Int64 instId, ChunkConfig config) { }
	// RVA: 0x21ca6a8 VA: 0x75947e26a8
	public static Void ModifyMusicChunkById(Int64 instId, String musicId) { }
	// RVA: 0x21ca7d4 VA: 0x75947e27d4
	public static Void RemoveMusicChunk(Int64 instId) { }
	// RVA: 0x21ca890 VA: 0x75947e2890
	public static Void SyncPlayingMusic() { }
	// RVA: 0x21c9a7c VA: 0x75947e1a7c
	private Void _SyncPlayingMusicImpl() { }
	// RVA: 0x21ca950 VA: 0x75947e2950
	private Void _ApplyEffect(Int64 chunkID, IMusicEffect effect) { }
	// RVA: 0x21caba4 VA: 0x75947e2ba4
	private static String _ConvertToAudioModule(PlayModuleType type) { }
	// RVA: 0x21cac70 VA: 0x75947e2c70
	public static Boolean TryGetMusicParamInfo(MusicParam param, out String name, out Single defaultVal) { }
	// RVA: 0x21cad9c VA: 0x75947e2d9c
	private static Void .cctor() { }
}
```