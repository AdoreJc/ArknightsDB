# UIMusicConfigCache

**Namespace:** `Torappu.UI`


## Methods

- `Boolean TryGetMusicId(IUIMusicConfig, out)`

- `Void SaveMusicToConfig(IUIMusicConfig, String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIMusicConfigCache : Singleton`1
{
	private Data`1 m_memCache; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0__GetMemCache; // 0x8
	private static DelegateBridge __Hotfix0_TryGetMusicId; // 0x10
	private static DelegateBridge __Hotfix0_SaveMusicToConfig; // 0x18


	// RVA: 0x21c877c VA: 0x75947e077c
	private Void .ctor() { }
	// RVA: 0x21c880c VA: 0x75947e080c
	private Data`1 _GetMemCache() { }
	// RVA: 0x21c8944 VA: 0x75947e0944
	public Boolean TryGetMusicId(IUIMusicConfig config, out String musicId) { }
	// RVA: 0x21c8acc VA: 0x75947e0acc
	public Void SaveMusicToConfig(IUIMusicConfig config, String musicId) { }
}
```