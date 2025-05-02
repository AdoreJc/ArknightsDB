# UIMusicDuckingHelper

**Namespace:** `Torappu.UI`


## Fields

- `AudioChannelEffect m_duckingEffect`


## Methods

- `Void SetMusicDuckingByMusicId(String)`

- `Void SetMusicDuckingByBank(String)`

- `Void ReverseMusicDucking()`

- `Void _RemoveMusicDucking()`

- `AudioFadeParam _GeneDuckingFadeParam(DuckingData)`

- `Void Dispose()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UIMusicDuckingHelper : IDisposable, IHotfixable
{
	private AudioChannelEffect m_duckingEffect; // 0x10
	private static DelegateBridge __Hotfix0_SetMusicDuckingByMusicId; // 0x0
	private static DelegateBridge __Hotfix0_SetMusicDuckingByBank; // 0x8
	private static DelegateBridge __Hotfix0_ReverseMusicDucking; // 0x10
	private static DelegateBridge __Hotfix0__RemoveMusicDucking; // 0x18
	private static DelegateBridge __Hotfix0__GeneDuckingFadeParam; // 0x20
	private static DelegateBridge __Hotfix0_Dispose; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30


	// RVA: 0x21c8cf0 VA: 0x75947e0cf0
	public Void SetMusicDuckingByMusicId(String musicId) { }
	// RVA: 0x21c8dc4 VA: 0x75947e0dc4
	public Void SetMusicDuckingByBank(String bankName) { }
	// RVA: 0x21c9234 VA: 0x75947e1234
	public Void ReverseMusicDucking() { }
	// RVA: 0x21c92b4 VA: 0x75947e12b4
	private Void _RemoveMusicDucking() { }
	// RVA: 0x21c90c8 VA: 0x75947e10c8
	private AudioFadeParam _GeneDuckingFadeParam(DuckingData duckingData) { }
	// RVA: 0x21c9340 VA: 0x75947e1340
	public Void Dispose() { }
	// RVA: 0x21c93a8 VA: 0x75947e13a8
	public Void .ctor() { }
}
```