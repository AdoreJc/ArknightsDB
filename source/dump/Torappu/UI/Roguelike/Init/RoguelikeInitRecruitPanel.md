# RoguelikeInitRecruitPanel

**Namespace:** `Torappu.UI.Roguelike.Init`


## Fields

- `RectTransform _listRoot`

- `AnimationWrapper _anim`

- `Transform _btnContainer`

- `RoguelikeInitConfirmBtn m_confirmBtn`

- `RoguelikeInitConfirmBtn m_confirmBtnPrefab`


## Properties

- `RoguelikeInitConfirmBtn confirmBtnPrefab`


## Methods

- `RoguelikeInitRecruit _CreateRecruit()`

- `Void _EventOnConfirm()`

- `Void set_confirmBtnPrefab(RoguelikeInitConfirmBtn)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Roguelike.Init
public class RoguelikeInitRecruitPanel : RoguelikeInitStepPanel`1
{
	private RectTransform _listRoot; // 0x38
	private AnimationWrapper _anim; // 0x40
	private Transform _btnContainer; // 0x48
	private const String ALL_RECUIT_ANIM; // 0x0
	private ItemPool`1 m_recruits; // 0x50
	private RoguelikeInitConfirmBtn m_confirmBtn; // 0x58
	private RoguelikeInitConfirmBtn m_confirmBtnPrefab; // 0x60
	private static DelegateBridge __Hotfix0__CreateRecruit; // 0x0
	private static DelegateBridge __Hotfix0__EventOnConfirm; // 0x8
	private static DelegateBridge __Hotfix0_OnUpdateContext; // 0x10
	private static DelegateBridge __Hotfix0_set_confirmBtnPrefab; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public RoguelikeInitConfirmBtn confirmBtnPrefab { set; }

	// RVA: 0x2b88734 VA: 0x75951a0734
	private RoguelikeInitRecruit _CreateRecruit() { }
	// RVA: 0x2b88970 VA: 0x75951a0970
	private Void _EventOnConfirm() { }
	// RVA: 0x2b889fc VA: 0x75951a09fc
	protected override Void OnUpdateContext(Boolean isNew) { }
	// RVA: 0x2b88e1c VA: 0x75951a0e1c
	public Void set_confirmBtnPrefab(RoguelikeInitConfirmBtn value) { }
	// RVA: 0x2b88ea0 VA: 0x75951a0ea0
	public Void .ctor() { }
}
```