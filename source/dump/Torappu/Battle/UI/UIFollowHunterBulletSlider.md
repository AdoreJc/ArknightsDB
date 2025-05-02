# UIFollowHunterBulletSlider

**Namespace:** `Torappu.Battle.UI`


## Fields

- `UIBulletBar _bulletBar`

- `CanvasGroup _canvasGroup`

- `Transform _root`

- `Transform _effectRoot`

- `Single _fadeInTime`

- `Single _fadeOutTime`

- `Single _targetAddTime`

- `String _effectKey`

- `Boolean m_hasDisplayed`

- `Int32 m_lastCnt`

- `Tween m_addCountTween`

- `HunterBulletBarPluginTalent m_bulletTalent`


## Methods

- `Void Init()`

- `Void UpdateCharacter()`

- `Void _FinishCountTweenIfNot()`

- `Void OnDestroy()`

- `Void Update()`

- `Void <>xLuaBaseProxy_OnAllocate()`

- `Void <>xLuaBaseProxy_DoAttach(Unit, UIPluginTalent)`

- `Void <>xLuaBaseProxy_DoDetach()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Battle.UI
public class UIFollowHunterBulletSlider : UnitTalentUIPlugin
{
	private UIBulletBar _bulletBar; // 0x30
	private CanvasGroup _canvasGroup; // 0x38
	private Transform _root; // 0x40
	private Transform _effectRoot; // 0x48
	private Single _fadeInTime; // 0x50
	private Single _fadeOutTime; // 0x54
	private Single _targetAddTime; // 0x58
	private String _effectKey; // 0x60
	private Boolean m_hasDisplayed; // 0x68
	private Int32 m_lastCnt; // 0x6c
	private Tween m_addCountTween; // 0x70
	private HunterBulletBarPluginTalent m_bulletTalent; // 0x78
	private static DelegateBridge __Hotfix0_Init; // 0x0
	private static DelegateBridge __Hotfix0_OnAllocate; // 0x8
	private static DelegateBridge __Hotfix0_DoAttach; // 0x10
	private static DelegateBridge __Hotfix0_DoDetach; // 0x18
	private static DelegateBridge __Hotfix0_UpdateCharacter; // 0x20
	private static DelegateBridge __Hotfix0__FinishCountTweenIfNot; // 0x28
	private static DelegateBridge __Hotfix0_OnDestroy; // 0x30
	private static DelegateBridge __Hotfix0_Update; // 0x38
	private static DelegateBridge _c__Hotfix0_ctor; // 0x40


	// RVA: 0x207e9b4 VA: 0x75946969b4
	public Void Init() { }
	// RVA: 0x207eb10 VA: 0x7594696b10
	public override Void OnAllocate() { }
	// RVA: 0x207eb9c VA: 0x7594696b9c
	protected override Void DoAttach(Unit owner, UIPluginTalent talent) { }
	// RVA: 0x207ecc8 VA: 0x7594696cc8
	protected override Void DoDetach() { }
	// RVA: 0x207ed44 VA: 0x7594696d44
	public Void UpdateCharacter() { }
	// RVA: 0x207ea58 VA: 0x7594696a58
	private Void _FinishCountTweenIfNot() { }
	// RVA: 0x207f220 VA: 0x7594697220
	private Void OnDestroy() { }
	// RVA: 0x207f2c0 VA: 0x75946972c0
	private Void Update() { }
	// RVA: 0x207f328 VA: 0x7594697328
	public Void .ctor() { }
	// RVA: 0x207f3b0 VA: 0x75946973b0
	private Void <>xLuaBaseProxy_OnAllocate() { }
	// RVA: 0x207f3b8 VA: 0x75946973b8
	private Void <>xLuaBaseProxy_DoAttach(Unit P0, UIPluginTalent P1) { }
	// RVA: 0x207f3c0 VA: 0x75946973c0
	private Void <>xLuaBaseProxy_DoDetach() { }
}
```