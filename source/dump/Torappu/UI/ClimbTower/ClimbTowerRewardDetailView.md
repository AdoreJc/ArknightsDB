# ClimbTowerRewardDetailView

**Namespace:** `Torappu.UI.ClimbTower`


## Fields

- `Text _textLowerItemName`

- `Text _textHigherItemName`

- `SimpleLayoutContent _columnContainer`

- `Boolean m_isInited`

- `Adapter m_adapter`


## Methods

- `Void _InitIfNot()`

- `Void Render()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.ClimbTower
public class ClimbTowerRewardDetailView : MonoBehaviour, IHotfixable
{
	private Text _textLowerItemName; // 0x18
	private Text _textHigherItemName; // 0x20
	private SimpleLayoutContent _columnContainer; // 0x28
	private Boolean m_isInited; // 0x30
	private Adapter m_adapter; // 0x38
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2c6a400 VA: 0x7595282400
	private Void _InitIfNot() { }
	// RVA: 0x2c6a570 VA: 0x7595282570
	public Void Render() { }
	// RVA: 0x2c6a6ac VA: 0x75952826ac
	public Void .ctor() { }
}
```