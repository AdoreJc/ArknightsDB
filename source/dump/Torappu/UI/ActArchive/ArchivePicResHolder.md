# ArchivePicResHolder

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `Sprite _picTitle`

- `Boolean _useBkg`


## Properties

- `Sprite picTitle`

- `Boolean useBkg`


## Methods

- `Sprite get_picTitle()`

- `Boolean get_useBkg()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ArchivePicResHolder : MonoBehaviour, IActArchiveSubResHolder, IHotfixable
{
	private Sprite _picTitle; // 0x18
	private Boolean _useBkg; // 0x20
	private static DelegateBridge __Hotfix0_get_picTitle; // 0x0
	private static DelegateBridge __Hotfix0_get_useBkg; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public Sprite picTitle { get; }
	public Boolean useBkg { get; }

	// RVA: 0x306a20c VA: 0x759568220c
	public Sprite get_picTitle() { }
	// RVA: 0x306a1a4 VA: 0x75956821a4
	public Boolean get_useBkg() { }
	// RVA: 0x306d840 VA: 0x7595685840
	public Void .ctor() { }
}
```