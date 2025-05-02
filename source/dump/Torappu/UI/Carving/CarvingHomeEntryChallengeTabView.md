# CarvingHomeEntryChallengeTabView

**Namespace:** `Torappu.UI.Carving`


## Fields

- `Image _imgIcon`

- `Boolean m_hasInited`

- `UIPageFinder m_pageFinder`


## Methods

- `Void Render(CarvingHomeEntryItemViewModel)`

- `Void ResetStatus()`

- `Tween GenerateAnim(AnimType)`

- `Void _InitIfNot()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Carving
public class CarvingHomeEntryChallengeTabView : MonoBehaviour, IHotfixable
{
	private AnimConfig[] _animConfigList; // 0x18
	private Image _imgIcon; // 0x20
	private EnumIntStructDictionary`2 m_animDict; // 0x28
	private Boolean m_hasInited; // 0x30
	private UIPageFinder m_pageFinder; // 0x38
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge __Hotfix0_ResetStatus; // 0x8
	private static DelegateBridge __Hotfix0_GenerateAnim; // 0x10
	private static DelegateBridge __Hotfix0__InitIfNot; // 0x18
	private static DelegateBridge _c__Hotfix0_ctor; // 0x20


	// RVA: 0x2d9207c VA: 0x75953aa07c
	public Void Render(CarvingHomeEntryItemViewModel itemModel) { }
	// RVA: 0x2d93194 VA: 0x75953ab194
	public Void ResetStatus() { }
	// RVA: 0x2d93250 VA: 0x75953ab250
	public Tween GenerateAnim(AnimType type) { }
	// RVA: 0x2d93084 VA: 0x75953ab084
	private Void _InitIfNot() { }
	// RVA: 0x2d9339c VA: 0x75953ab39c
	public Void .ctor() { }
}
```