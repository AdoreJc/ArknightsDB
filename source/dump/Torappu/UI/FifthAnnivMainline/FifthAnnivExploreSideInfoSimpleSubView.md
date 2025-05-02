# FifthAnnivExploreSideInfoSimpleSubView

**Namespace:** `Torappu.UI.FifthAnnivMainline`


## Fields

- `Text _teamNameText`

- `Text _teamCodeText`

- `Button _backBtn`

- `Int32 _tweenDelay`

- `UIAtlasObject _abilityIconAtlas`

- `Tween m_valueTween`

- `Action m_onBackBtnClick`

- `UIPageFinder m_pageFinder`


## Methods

- `Void Render(FifthAnnivExploreViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.FifthAnnivMainline
public class FifthAnnivExploreSideInfoSimpleSubView : MonoBehaviour, IHotfixable
{
	private Text _teamNameText; // 0x18
	private Text _teamCodeText; // 0x20
	private UIAtlasImage[] _teamValueIcons; // 0x28
	private Text[] _teamValueTexts; // 0x30
	private Button _backBtn; // 0x38
	private Int32 _tweenDelay; // 0x40
	private UIAtlasObject _abilityIconAtlas; // 0x48
	private Tween m_valueTween; // 0x50
	private Action m_onBackBtnClick; // 0x58
	private UIPageFinder m_pageFinder; // 0x60
	private Dictionary`2 m_prevAbilityValues; // 0x70
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x292e5a0 VA: 0x7594f465a0
	public Void Render(FifthAnnivExploreViewModel viewModel) { }
	// RVA: 0x292e8f8 VA: 0x7594f468f8
	public Void .ctor() { }
}
```