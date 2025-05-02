# ActArchiveResHolder

**Namespace:** `Torappu.UI.ActArchive`


## Fields

- `Sprite _bkg`


## Properties

- `Sprite bkg`


## Methods

- `Sprite get_bkg()`

- `T GetHolderComponent()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ActArchive
public class ActArchiveResHolder : MonoBehaviour, IHotfixable
{
	private GameObject[] _subResHolders; // 0x18
	private Sprite _bkg; // 0x20
	private Dictionary`2 m_subResHolders; // 0x28
	private static DelegateBridge __Hotfix0_get_bkg; // 0x0
	private static DelegateBridge __Hotfix0_GetHolderComponent; // 0x8
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public Sprite bkg { get; }

	// RVA: 0x30135b8 VA: 0x759562b5b8
	public Sprite get_bkg() { }
	// RVA: 0x VA: 0x0
	public T GetHolderComponent() { }
	// RVA: 0x3013620 VA: 0x759562b620
	private Void _InitIfNot() { }
	// RVA: 0x30138cc VA: 0x759562b8cc
	public Void .ctor() { }
}
```