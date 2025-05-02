# UICharacterInfoStatusSubPanelInLegion

**Namespace:** `Torappu.Battle.UI`


## Fields

- `Image _professionBacklight`

- `Image _professionNoInfo`

- `Text _professionDescription`

- `Text _professionDescriptionHead`

- `CanvasGroup _professionCanvasGroup`

- `ProfessionPanelState m_panelState`


## Methods

- `Void _RefreshProfessionPanelState(ProfessionPanelState)`

- `Void <>xLuaBaseProxy_SetData(ObjectPtr`1, ModeType, Card)`

- `Void <>xLuaBaseProxy_UpdateData(ObjectPtr`1, ModeType, Card)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class UICharacterInfoStatusSubPanelInLegion : UICharacterInfoStatusSubPanel
{
	private Image _professionBacklight; // 0xb0
	private Image _professionNoInfo; // 0xb8
	private Text _professionDescription; // 0xc0
	private Text _professionDescriptionHead; // 0xc8
	private CanvasGroup _professionCanvasGroup; // 0xd0
	private ProfessionPanelState m_panelState; // 0xd8
	private static DelegateBridge __Hotfix0_SetData; // 0x0
	private static DelegateBridge __Hotfix0__RefreshProfessionPanelState; // 0x8
	private static DelegateBridge __Hotfix0_UpdateData; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18


	// RVA: 0x2037ea4 VA: 0x759464fea4
	public override Void SetData(ObjectPtr`1 characterPtr, ModeType mode, Card card) { }
	// RVA: 0x20382f8 VA: 0x75946502f8
	private Void _RefreshProfessionPanelState(ProfessionPanelState state) { }
	// RVA: 0x2038410 VA: 0x7594650410
	public override Void UpdateData(ObjectPtr`1 characterPtr, ModeType mode, Card card) { }
	// RVA: 0x20385bc VA: 0x75946505bc
	public Void .ctor() { }
	// RVA: 0x2038628 VA: 0x7594650628
	private Void <>xLuaBaseProxy_SetData(ObjectPtr`1 P0, ModeType P1, Card P2) { }
	// RVA: 0x203862c VA: 0x759465062c
	private Void <>xLuaBaseProxy_UpdateData(ObjectPtr`1 P0, ModeType P1, Card P2) { }
}
```