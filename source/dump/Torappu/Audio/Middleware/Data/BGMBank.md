# BGMBank

**Namespace:** `Torappu.Audio.Middleware.Data`


## Fields

- `String intro`

- `String loop`

- `Single volume`

- `Single crossfade`

- `Single delay`

- `String fadeStyleId`


## Methods

- `String GetIntroAsset()`

- `String GetLoopAsset()`

- `Boolean IsSameAudio(IAudioInfo)`

- `Boolean ShouldSerializefadeStyleId()`

- `String GenerateSignature()`

- `BGMBank ShallowClone()`

- `Void <>xLuaBaseProxy_Preload(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Audio.Middleware.Data
public class BGMBank : Bank, IMusicInfo, IAudioInfo, IAliasBank
{
	private static BGMAudioAtom m_bgmAtom; // 0x0
	private const String FLOAT_FORMAT; // 0x0
	public String intro; // 0x30
	public String loop; // 0x38
	public Single volume; // 0x40
	public Single crossfade; // 0x44
	public Single delay; // 0x48
	public String fadeStyleId; // 0x50
	private static DelegateBridge __Hotfix0_GetIntroAsset; // 0x8
	private static DelegateBridge __Hotfix0_GetLoopAsset; // 0x10
	private static DelegateBridge __Hotfix0_IsSameAudio; // 0x18
	private static DelegateBridge __Hotfix0_Play; // 0x20
	private static DelegateBridge __Hotfix0_Preload; // 0x28
	private static DelegateBridge __Hotfix0_ShouldSerializefadeStyleId; // 0x30
	private static DelegateBridge __Hotfix0_GenerateSignature; // 0x38
	private static DelegateBridge __Hotfix0_ShallowClone; // 0x40
	private static DelegateBridge _c__Hotfix0_ctor; // 0x48


	// RVA: 0x3ee0a88 VA: 0x75964f8a88
	public String GetIntroAsset() { }
	// RVA: 0x3ee0b00 VA: 0x75964f8b00
	public String GetLoopAsset() { }
	// RVA: 0x3ee0b78 VA: 0x75964f8b78
	public Boolean IsSameAudio(IAudioInfo other) { }
	// RVA: 0x3ee0c0c VA: 0x75964f8c0c
	public override AudioAtom Play(Vector3 position) { }
	// RVA: 0x3ee0ea8 VA: 0x75964f8ea8
	public override Void Preload(String persistTag) { }
	// RVA: 0x3ee0fac VA: 0x75964f8fac
	public Boolean ShouldSerializefadeStyleId() { }
	// RVA: 0x3ee1034 VA: 0x75964f9034
	public String GenerateSignature() { }
	// RVA: 0x3ee1218 VA: 0x75964f9218
	public BGMBank ShallowClone() { }
	// RVA: 0x3ee12d0 VA: 0x75964f92d0
	public Void .ctor() { }
	// RVA: 0x3ee1358 VA: 0x75964f9358
	private static Void .cctor() { }
	// RVA: 0x3ee1464 VA: 0x75964f9464
	private Void <>xLuaBaseProxy_Preload(String P0) { }
}
```