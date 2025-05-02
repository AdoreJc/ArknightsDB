# UILegionBlastCardToastPanel

**Namespace:** `Torappu.Battle.UI`


## Fields

- `Image _cardIcon`

- `GameObject _multiIcon`

- `Text _blastDesc`

- `Text _multiBlastDesc`

- `Single m_lastTime`

- `StringBuilder m_nameList`


## Methods

- `Void OnDestroy()`

- `Void <>xLuaBaseProxy_OnUpdate()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class UILegionBlastCardToastPanel : UIToastSubPanel
{
	private Image _cardIcon; // 0x28
	private GameObject _multiIcon; // 0x30
	private Text _blastDesc; // 0x38
	private Text _multiBlastDesc; // 0x40
	private Single m_lastTime; // 0x48
	private StringBuilder m_nameList; // 0x50
	private const String COLOE_OF_CHAR_NAME; // 0x0
	private static DelegateBridge __Hotfix0_OnShow; // 0x0
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x8
	private static DelegateBridge __Hotfix0_OnUpdate; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x204375c VA: 0x759465b75c
	public override Void OnShow(Options options) { }
	// RVA: 0x2043a84 VA: 0x759465ba84
	private Void OnDestroy() { }
	// RVA: 0x2043afc VA: 0x759465bafc
	public override Void OnUpdate() { }
	// RVA: 0x2043d30 VA: 0x759465bd30
	public Void .ctor() { }
	// RVA: 0x2043e4c VA: 0x759465be4c
	private Void <>xLuaBaseProxy_OnUpdate() { }
}
```