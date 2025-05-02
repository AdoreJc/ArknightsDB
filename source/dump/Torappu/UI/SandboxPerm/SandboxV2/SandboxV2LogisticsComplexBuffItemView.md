# SandboxV2LogisticsComplexBuffItemView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `Image _imgProfession`

- `Text _txtBuffDesc`

- `SandboxV2LogisticsCharBeanView _charBeanView`

- `Text _txtBuffCount`

- `Color _colorCountDefault`

- `Color _colorCountNormal`

- `Color _colorCountOverflow`

- `GameObject _panelOverflow`

- `UIPageFinder m_pageFinder`


## Methods

- `Void Render(SandboxV2LogisticsBuffViewModel, SandboxV2LogisticsCharViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2LogisticsComplexBuffItemView : MonoBehaviour, IHotfixable
{
	private Image _imgProfession; // 0x18
	private Text _txtBuffDesc; // 0x20
	private SandboxV2LogisticsCharBeanView _charBeanView; // 0x28
	private Text _txtBuffCount; // 0x30
	private Color _colorCountDefault; // 0x38
	private Color _colorCountNormal; // 0x48
	private Color _colorCountOverflow; // 0x58
	private GameObject _panelOverflow; // 0x68
	private UIPageFinder m_pageFinder; // 0x70
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x25dbabc VA: 0x7594bf3abc
	public Void Render(SandboxV2LogisticsBuffViewModel buffViewModel, SandboxV2LogisticsCharViewModel charViewModel) { }
	// RVA: 0x25dc0a0 VA: 0x7594bf40a0
	public Void .ctor() { }
}
```