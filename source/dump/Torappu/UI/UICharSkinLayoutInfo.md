# UICharSkinLayoutInfo

**Namespace:** `Torappu.UI`


## Methods

- `Void Bake()`

- `Void _InitIfNot()`

- `Info GetLayoutInfo(String)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI
public class UICharSkinLayoutInfo : ScriptableObject, IHotfixable
{
	private List`1 _illustIds; // 0x18
	private List`1 _infos; // 0x20
	private Dictionary`2 m_infoMap; // 0x28
	private static DelegateBridge __Hotfix0_Bake; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0__CheckIfContentChanged; // 0x10
	private static DelegateBridge __Hotfix0__GenIllustLayoutMap; // 0x18
	private static DelegateBridge __Hotfix0_GetLayoutInfo; // 0x20
	private static DelegateBridge _c__Hotfix0_ctor; // 0x28


	// RVA: 0x211e29c VA: 0x759473629c
	public Void Bake() { }
	// RVA: 0x211e300 VA: 0x7594736300
	private Void _InitIfNot() { }
	// RVA: 0x211e584 VA: 0x7594736584
	private static Boolean _CheckIfContentChanged(Dictionary`2 lhs, Dictionary`2 rhs) { }
	// RVA: 0x211e390 VA: 0x7594736390
	private Dictionary`2 _GenIllustLayoutMap() { }
	// RVA: 0x211e97c VA: 0x759473697c
	public Info GetLayoutInfo(String illustId) { }
	// RVA: 0x211ea7c VA: 0x7594736a7c
	public Void .ctor() { }
}
```