# SandboxV2TopBarResItemView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `Image _resIcon`

- `Text _resName`

- `Text _resCount`

- `Boolean _useSecondResMax`

- `UIPageFinder m_pageFinder`

- `String m_topicId`


## Methods

- `Void Render(String, UIItemViewModel)`

- `String _FormatCount(Int32, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2TopBarResItemView : MonoBehaviour, IHotfixable
{
	private const Int32 SECOND_RES_MAX_COUNT; // 0x0
	private const Int32 GOLD_RES_MAX_COUNT; // 0x0
	private Image _resIcon; // 0x18
	private Text _resName; // 0x20
	private Text _resCount; // 0x28
	private Boolean _useSecondResMax; // 0x30
	private UIPageFinder m_pageFinder; // 0x38
	private String m_topicId; // 0x48
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0__FormatCount; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x254d9b8 VA: 0x7594b659b8
	public Void Render(String topicId, UIItemViewModel viewModel) { }
	// RVA: 0x254e718 VA: 0x7594b66718
	private String _FormatCount(Int32 count, Boolean useSecResMax) { }
	// RVA: 0x254e82c VA: 0x7594b6682c
	public Void .ctor() { }
}
```