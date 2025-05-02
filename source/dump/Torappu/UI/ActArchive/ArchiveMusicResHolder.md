# ArchiveMusicResHolder

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `Sprite _musicTitle`

- `Sprite _cdLeft`

- `Sprite _cdLeftLogo`

- `Sprite _cdRight`

- `Sprite _cdRightLogo`


## Properties

- `Sprite musicTitle`

- `Sprite cdLeft`

- `Sprite cdLeftLogo`

- `Sprite cdRight`

- `Sprite cdRightLogo`


## Methods

- `Sprite get_musicTitle()`

- `Sprite get_cdLeft()`

- `Sprite get_cdLeftLogo()`

- `Sprite get_cdRight()`

- `Sprite get_cdRightLogo()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchiveMusicResHolder : MonoBehaviour, IActArchiveSubResHolder, IHotfixable
{
	private Sprite _musicTitle; // 0x18
	private Sprite _cdLeft; // 0x20
	private Sprite _cdLeftLogo; // 0x28
	private Sprite _cdRight; // 0x30
	private Sprite _cdRightLogo; // 0x38
	private static DelegateBridge __Hotfix0_get_musicTitle; // 0x0
	private static DelegateBridge __Hotfix0_get_cdLeft; // 0x8
	private static DelegateBridge __Hotfix0_get_cdLeftLogo; // 0x10
	private static DelegateBridge __Hotfix0_get_cdRight; // 0x18
	private static DelegateBridge __Hotfix0_get_cdRightLogo; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28

	public Sprite musicTitle { get; }
	public Sprite cdLeft { get; }
	public Sprite cdLeftLogo { get; }
	public Sprite cdRight { get; }
	public Sprite cdRightLogo { get; }

	// RVA: 0x305dfbc VA: 0x7595675fbc
	public Sprite get_musicTitle() { }
	// RVA: 0x305e024 VA: 0x7595676024
	public Sprite get_cdLeft() { }
	// RVA: 0x305e0f4 VA: 0x75956760f4
	public Sprite get_cdLeftLogo() { }
	// RVA: 0x305e08c VA: 0x759567608c
	public Sprite get_cdRight() { }
	// RVA: 0x305e15c VA: 0x759567615c
	public Sprite get_cdRightLogo() { }
	// RVA: 0x306357c VA: 0x759567b57c
	public Void .ctor() { }
}
```