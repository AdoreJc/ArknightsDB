# CommonChooseCharRowComp

**Namespace:** `Torappu.UI.ChooseChar`


## Fields

- `Single _baseHeight`

- `Single _ownTagHeight`

- `SimpleLayoutContent _simpleLayout`

- `GameObject _ownedPanel`

- `GameObject _notOwnedPanel`

- `Boolean m_isInited`

- `CharCardAdapter m_adapter`


## Methods

- `Void Render(ViewModel)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ChooseChar
public class CommonChooseCharRowComp : MonoBehaviour, IHotfixable
{
	private Single _baseHeight; // 0x18
	private Single _ownTagHeight; // 0x1c
	private SimpleLayoutContent _simpleLayout; // 0x20
	private GameObject _ownedPanel; // 0x28
	private GameObject _notOwnedPanel; // 0x30
	private Boolean m_isInited; // 0x38
	private CharCardAdapter m_adapter; // 0x40
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2c3c914 VA: 0x7595254914
	public Void Render(ViewModel viewModel) { }
	// RVA: 0x2c3ca34 VA: 0x7595254a34
	private Void _InitIfNot() { }
	// RVA: 0x2c3cb70 VA: 0x7595254b70
	public Void .ctor() { }
}
```