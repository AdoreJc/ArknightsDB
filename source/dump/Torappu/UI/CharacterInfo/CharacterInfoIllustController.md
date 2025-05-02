# CharacterInfoIllustController

**Namespace:** `Torappu.UI.CharacterInfo`


## Fields

- `GameObject _illustWrapperPrefab`

- `Transform _illustLayout`

- `IllustCache m_cache`

- `CharacterInfoIllustWrapper m_illustWrappers`

- `UIPageFinder m_pageFinder`


## Properties

- `UICharacterIllust illust`


## Methods

- `UICharacterIllust get_illust()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CharacterInfo
public class CharacterInfoIllustController : DataBinder`1
{
	private GameObject _illustWrapperPrefab; // 0x20
	private Transform _illustLayout; // 0x28
	private IllustCache m_cache; // 0x30
	private CharacterInfoIllustWrapper m_illustWrappers; // 0x50
	private UIPageFinder m_pageFinder; // 0x58
	private static DelegateBridge __Hotfix0_get_illust; // 0x0
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10

	public UICharacterIllust illust { get; }

	// RVA: 0x2d7108c VA: 0x759538908c
	public UICharacterIllust get_illust() { }
	// RVA: 0x2d711b0 VA: 0x75953891b0
	public override Void OnValueChanged(CharacterIllustViewProperty property) { }
	// RVA: 0x2d71640 VA: 0x7595389640
	public Void .ctor() { }
}
```