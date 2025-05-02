# BattleFinishSixStarDropRewardFrameView

**Namespace:** `Torappu.UI.BattleFinish`


## Fields

- `Single _fadeDurationPerItem`

- `Single _widthChangeDurationPerItem`

- `CanvasGroup _frame`

- `RectTransform m_holderRoot`

- `Boolean m_enableChangeWidth`

- `Int32 m_itemAvailCount`


## Methods

- `Void Update()`

- `Void _UpdateWidth()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.BattleFinish
public class BattleFinishSixStarDropRewardFrameView : BattleFinishDropRewardFrameView
{
	private const Int32 PADDING_LEFT; // 0x0
	private const Int32 PADDING_RIGHT; // 0x0
	private Single _fadeDurationPerItem; // 0x18
	private Single _widthChangeDurationPerItem; // 0x1c
	private CanvasGroup _frame; // 0x20
	private RectTransform m_holderRoot; // 0x28
	private Boolean m_enableChangeWidth; // 0x30
	private Int32 m_itemAvailCount; // 0x34
	private static DelegateBridge __Hotfix0_Update; // 0x0
	private static DelegateBridge __Hotfix0__UpdateWidth; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_SetLayout; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2e94478 VA: 0x75954ac478
	private Void Update() { }
	// RVA: 0x2e944e0 VA: 0x75954ac4e0
	private Void _UpdateWidth() { }
	// RVA: 0x2e946b4 VA: 0x75954ac6b4
	public override Void Render(BattleFinishDropRewardFrameHolder battleFinishDropRewardFrameHolder, DropInfoGroupViewModel dropInfoGroupViewModel) { }
	// RVA: 0x2e9486c VA: 0x75954ac86c
	public override Void SetLayout(LayoutGroup layoutGroup) { }
	// RVA: 0x2e94958 VA: 0x75954ac958
	public Void .ctor() { }
}
```