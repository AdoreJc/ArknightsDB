# UIBattleLoadingDecor

**Namespace:** `Torappu.Battle.UI`


## Fields

- `UIStageInfo _stageInfo`

- `Boolean _hideOriginDecor`

- `Boolean _hideCover`

- `UITipsHolderForBattle _tipsHolder`


## Properties

- `Boolean hideOriginDecor`

- `Boolean hideCover`


## Methods

- `Boolean get_hideOriginDecor()`

- `Boolean get_hideCover()`

- `Void Render(BattleStageInfo)`

- `Void OnDestroy()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class UIBattleLoadingDecor : MonoBehaviour, IHotfixable
{
	private UIStageInfo _stageInfo; // 0x18
	private Boolean _hideOriginDecor; // 0x20
	private Boolean _hideCover; // 0x21
	private UITipsHolderForBattle _tipsHolder; // 0x28
	private UIAnimationLocation[] _loopAnims; // 0x30
	private List`1 m_animTweens; // 0x38
	private static DelegateBridge __Hotfix0_get_hideOriginDecor; // 0x0
	private static DelegateBridge __Hotfix0_get_hideCover; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public Boolean hideOriginDecor { get; }
	public Boolean hideCover { get; }

	// RVA: 0x2040d70 VA: 0x7594658d70
	public Boolean get_hideOriginDecor() { }
	// RVA: 0x2040dd8 VA: 0x7594658dd8
	public Boolean get_hideCover() { }
	// RVA: 0x2040a38 VA: 0x7594658a38
	public Void Render(BattleStageInfo stageInfo) { }
	// RVA: 0x2041440 VA: 0x7594659440
	private Void OnDestroy() { }
	// RVA: 0x204152c VA: 0x759465952c
	public Void .ctor() { }
}
```