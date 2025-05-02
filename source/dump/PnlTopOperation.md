# PnlTopOperation

**Namespace:** ` `


## Fields

- `GameObject _root`

- `Text _textMoneyCount`

- `Text _textPlayerRank`

- `Text _textMoneyExpect`

- `UIAnimationLocation _animMoneyExpect`

- `Single _moneyExpectNumTweenDuration`

- `Color _colorEmptyRank`

- `Color _colorNormalRank`

- `AnimationSwitchTween m_moneyExpectShowTween`

- `Tween m_moneyExpectNumTween`

- `Int32 m_currMoneyExpectShowNum`

- `Boolean m_inited`


## Methods

- `Void _InitIfNot()`

- `Void Render(EnemyDuelBetViewModel, Boolean)`

- `Void <_InitIfNot>b__14_0()`

- `Int32 <Render>b__15_0()`

- `Void <Render>b__15_1(Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : 
private class PnlTopOperation : IHotfixable
{
	private const String MONEY_EXPECT_FORMAT; // 0x0
	private const String RANK_EMPTY_DESC; // 0x0
	private GameObject _root; // 0x10
	private Text _textMoneyCount; // 0x18
	private Text _textPlayerRank; // 0x20
	private Text _textMoneyExpect; // 0x28
	private UIAnimationLocation _animMoneyExpect; // 0x30
	private Single _moneyExpectNumTweenDuration; // 0x40
	private Color _colorEmptyRank; // 0x44
	private Color _colorNormalRank; // 0x54
	private AnimationSwitchTween m_moneyExpectShowTween; // 0x68
	private Tween m_moneyExpectNumTween; // 0x70
	private Int32 m_currMoneyExpectShowNum; // 0x78
	private Boolean m_inited; // 0x7c
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x0
	private static DelegateBridge __Hotfix0_Render; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2982038 VA: 0x7594f9a038
	private Void _InitIfNot() { }
	// RVA: 0x2980ba8 VA: 0x7594f98ba8
	public Void Render(EnemyDuelBetViewModel model, Boolean isInit) { }
	// RVA: 0x29821dc VA: 0x7594f9a1dc
	public Void .ctor() { }
	// RVA: 0x2982254 VA: 0x7594f9a254
	private Void <_InitIfNot>b__14_0() { }
	// RVA: 0x298225c VA: 0x7594f9a25c
	private Int32 <Render>b__15_0() { }
	// RVA: 0x2982264 VA: 0x7594f9a264
	private Void <Render>b__15_1(Int32 val) { }
}
```