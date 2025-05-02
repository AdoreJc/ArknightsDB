# BossRushStageDetailDropPanel

**Namespace:** `Torappu.UI.BossRush`


## Fields

- `UIReentrantFloatPanel _panel`

- `Image _imgDropInfo`

- `RectTransform _panelBackBtn`

- `Boolean m_hasInited`


## Methods

- `Void Render(String)`

- `Void Show()`

- `Void Hide()`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.BossRush
public class BossRushStageDetailDropPanel : MonoBehaviour, IHotfixable
{
	private UIReentrantFloatPanel _panel; // 0x18
	private Image _imgDropInfo; // 0x20
	private RectTransform _panelBackBtn; // 0x28
	private Boolean m_hasInited; // 0x30
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_Show; // 0x8
	private static DelegateBridge __Hotfix0_Hide; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2e72498 VA: 0x759548a498
	public Void Render(String actId) { }
	// RVA: 0x2e726a8 VA: 0x759548a6a8
	public Void Show() { }
	// RVA: 0x2e7271c VA: 0x759548a71c
	public Void Hide() { }
	// RVA: 0x2e725a4 VA: 0x759548a5a4
	private Void _InitIfNot() { }
	// RVA: 0x2e72790 VA: 0x759548a790
	public Void .ctor() { }
}
```