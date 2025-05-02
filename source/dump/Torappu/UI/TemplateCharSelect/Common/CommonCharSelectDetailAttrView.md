# CommonCharSelectDetailAttrView

**Namespace:** `Torappu.UI.TemplateCharSelect.Common`


## Fields

- `Image _iconMaxHp`

- `Image _iconAtk`

- `Image _iconDef`

- `Image _iconRes`

- `Image _iconReviveTime`

- `Image _iconCost`

- `Image _iconBlockNum`

- `Image _iconAtkSpeed`

- `Text _maxHp`

- `Text _atk`

- `Text _def`

- `Text _res`

- `Text _reviveTimeDesc`

- `Text _cost`

- `Text _blockNum`

- `Text _attackSpeedDesc`

- `UIPageFinder m_pageFinder`


## Properties

- `Int32 maxHp`

- `Int32 atk`

- `Int32 def`

- `Single magicRes`

- `Int32 reviveTime`

- `Int32 cost`

- `Int32 blockNum`

- `String attackSpdDesc`


## Methods

- `Void set_maxHp(Int32)`

- `Void set_atk(Int32)`

- `Void set_def(Int32)`

- `Void set_magicRes(Single)`

- `Void set_reviveTime(Int32)`

- `Void set_cost(Int32)`

- `Void set_blockNum(Int32)`

- `Void set_attackSpdDesc(String)`

- `Void InitAttrIconSprite()`

- `Void _SetAttrSprite(Image, CharacterSortType)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.TemplateCharSelect.Common
public class CommonCharSelectDetailAttrView : MonoBehaviour, IHotfixable
{
	private Image _iconMaxHp; // 0x18
	private Image _iconAtk; // 0x20
	private Image _iconDef; // 0x28
	private Image _iconRes; // 0x30
	private Image _iconReviveTime; // 0x38
	private Image _iconCost; // 0x40
	private Image _iconBlockNum; // 0x48
	private Image _iconAtkSpeed; // 0x50
	private Text _maxHp; // 0x58
	private Text _atk; // 0x60
	private Text _def; // 0x68
	private Text _res; // 0x70
	private Text _reviveTimeDesc; // 0x78
	private Text _cost; // 0x80
	private Text _blockNum; // 0x88
	private Text _attackSpeedDesc; // 0x90
	private UIPageFinder m_pageFinder; // 0x98
	private static DelegateBridge __Hotfix0_set_maxHp; // 0x0
	private static DelegateBridge __Hotfix0_set_atk; // 0x8
	private static DelegateBridge __Hotfix0_set_def; // 0x10
	private static DelegateBridge __Hotfix0_set_magicRes; // 0x18
	private static DelegateBridge __Hotfix0_set_reviveTime; // 0x20
	private static DelegateBridge __Hotfix0_set_cost; // 0x28
	private static DelegateBridge __Hotfix0_set_blockNum; // 0x30
	private static DelegateBridge __Hotfix0_set_attackSpdDesc; // 0x38
	private static DelegateBridge __Hotfix0_InitAttrIconSprite; // 0x40
	private static DelegateBridge __Hotfix0__SetAttrSprite; // 0x48
	private static DelegateBridge _c__Hotfix0_ctor; // 0x50

	public Int32 maxHp { set; }
	public Int32 atk { set; }
	public Int32 def { set; }
	public Single magicRes { set; }
	public Int32 reviveTime { set; }
	public Int32 cost { set; }
	public Int32 blockNum { set; }
	public String attackSpdDesc { set; }

	// RVA: 0x2c53790 VA: 0x759526b790
	public Void set_maxHp(Int32 value) { }
	// RVA: 0x2c5383c VA: 0x759526b83c
	public Void set_atk(Int32 value) { }
	// RVA: 0x2c538e8 VA: 0x759526b8e8
	public Void set_def(Int32 value) { }
	// RVA: 0x2c53994 VA: 0x759526b994
	public Void set_magicRes(Single value) { }
	// RVA: 0x2c53a40 VA: 0x759526ba40
	public Void set_reviveTime(Int32 value) { }
	// RVA: 0x2c53ae4 VA: 0x759526bae4
	public Void set_cost(Int32 value) { }
	// RVA: 0x2c53b90 VA: 0x759526bb90
	public Void set_blockNum(Int32 value) { }
	// RVA: 0x2c53c3c VA: 0x759526bc3c
	public Void set_attackSpdDesc(String value) { }
	// RVA: 0x2c53cd0 VA: 0x759526bcd0
	public Void InitAttrIconSprite() { }
	// RVA: 0x2c53db0 VA: 0x759526bdb0
	private Void _SetAttrSprite(Image imgIcon, CharacterSortType sortType) { }
	// RVA: 0x2c53eac VA: 0x759526beac
	public Void .ctor() { }
}
```