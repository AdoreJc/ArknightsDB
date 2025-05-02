# Act42D0MapStageSelectItemView

**Namespace:** `Torappu.Activity.Act42D0`


## Fields

- `Text _stageNum`

- `UIAtlasImage _areaCode`

- `UIAtlasImage _areaCodeBkg`

- `UIAtlasImage _imgOperation`

- `GameObject _imgCompleted`

- `UIAtlasImage _imgBkgNotSelected`

- `GameObject _bkgSelectedNormal`

- `GameObject _bkgSelectedHard`

- `UIAtlasObject _atlasAsset`

- `String _imgNameBkgNotKeyStage`

- `String _imgNameBkgKeyStage`

- `Color _colorStageNumNotSelected`

- `Color _colorStageNumSelected`

- `Color _colorAreaCodeHard`

- `Color _colorAreaCodeNormal`

- `Color _colorAreaCodeNotSelected`

- `Color _colorTagOperationNotSelected`

- `Color _colorTagOperationSelected`

- `Color _colorAreaCodeBkgSelected`

- `Color _colorAreaCodeBkgNotSelected`

- `UIAnimationLocation _animSelected`

- `GameObject _btnGo`

- `Boolean m_isInited`

- `UIPageFinder m_pageFinder`

- `Int32 m_index`

- `AnimationSwitchTween m_switchTween`


## Properties

- `GameObject btnGo`


## Methods

- `GameObject get_btnGo()`

- `Void _InitIfNot()`

- `Void Render(Act42D0MapStageItemViewModel, Boolean, Boolean, Int32, Boolean)`

- `Void OnClick()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.Activity.Act42D0
public class Act42D0MapStageSelectItemView : MonoBehaviour, IHotfixable
{
	private Text _stageNum; // 0x18
	private UIAtlasImage _areaCode; // 0x20
	private UIAtlasImage _areaCodeBkg; // 0x28
	private UIAtlasImage _imgOperation; // 0x30
	private GameObject _imgCompleted; // 0x38
	private UIAtlasImage _imgBkgNotSelected; // 0x40
	private GameObject _bkgSelectedNormal; // 0x48
	private GameObject _bkgSelectedHard; // 0x50
	private UIAtlasObject _atlasAsset; // 0x58
	private String _imgNameBkgNotKeyStage; // 0x60
	private String _imgNameBkgKeyStage; // 0x68
	private Color _colorStageNumNotSelected; // 0x70
	private Color _colorStageNumSelected; // 0x80
	private Color _colorAreaCodeHard; // 0x90
	private Color _colorAreaCodeNormal; // 0xa0
	private Color _colorAreaCodeNotSelected; // 0xb0
	private Color _colorTagOperationNotSelected; // 0xc0
	private Color _colorTagOperationSelected; // 0xd0
	private Color _colorAreaCodeBkgSelected; // 0xe0
	private Color _colorAreaCodeBkgNotSelected; // 0xf0
	private UIAnimationLocation _animSelected; // 0x100
	private GameObject _btnGo; // 0x110
	private Boolean m_isInited; // 0x118
	private UIPageFinder m_pageFinder; // 0x120
	private Int32 m_index; // 0x130
	private AnimationSwitchTween m_switchTween; // 0x138
	private static DelegateBridge __Hotfix0_get_btnGo; // 0x0
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x8
	private static DelegateBridge __Hotfix0_Render; // 0x10
	private static DelegateBridge __Hotfix0_OnClick; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20

	public GameObject btnGo { get; }

	// RVA: 0x321b56c VA: 0x759583356c
	public GameObject get_btnGo() { }
	// RVA: 0x321ce60 VA: 0x7595834e60
	private Void _InitIfNot() { }
	// RVA: 0x321bcec VA: 0x7595833cec
	public Void Render(Act42D0MapStageItemViewModel data, Boolean isHard, Boolean isSelected, Int32 index, Boolean areaChanged) { }
	// RVA: 0x321cf4c VA: 0x7595834f4c
	public Void OnClick() { }
	// RVA: 0x321d054 VA: 0x7595835054
	public Void .ctor() { }
}
```