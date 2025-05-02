# DIYFurnitureMusicController

**Namespace:** `Torappu.Building.DIY`


## Fields

- `UIMusicDuckingHelper m_musicDuckingHelper`

- `AudioMusicGroupHandler m_musicGroupHandler`

- `String m_cachedMusicId`


## Methods

- `Void PlayFurnitureMusic(String)`

- `Void StopFurnitureMusic()`

- `Void Dispose()`

- `Void _PlayFurnitureMusicWithDucking(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Building.DIY
public class DIYFurnitureMusicController : SingletonInScene`1, IDisposable
{
	private UIMusicDuckingHelper m_musicDuckingHelper; // 0x18
	private AudioMusicGroupHandler m_musicGroupHandler; // 0x20
	private String m_cachedMusicId; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x0
	private static DelegateBridge __Hotfix0_PlayFurnitureMusic; // 0x8
	private static DelegateBridge __Hotfix0_StopFurnitureMusic; // 0x10
	private static DelegateBridge __Hotfix0_Dispose; // 0x18
	private static DelegateBridge __Hotfix0__PlayFurnitureMusicWithDucking; // 0x20


	// RVA: 0x37b31a8 VA: 0x7595dcb1a8
	private Void .ctor() { }
	// RVA: 0x37b3238 VA: 0x7595dcb238
	public Void PlayFurnitureMusic(String musicId) { }
	// RVA: 0x37b32e0 VA: 0x7595dcb2e0
	public Void StopFurnitureMusic() { }
	// RVA: 0x37b3508 VA: 0x7595dcb508
	public Void Dispose() { }
	// RVA: 0x37b338c VA: 0x7595dcb38c
	private Void _PlayFurnitureMusicWithDucking(String musicId) { }
}
```