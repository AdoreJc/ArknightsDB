# SandboxV2ZoneView

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `UIAtlasImage _imageZoneWeather`

- `Image _imageZoneName`

- `UIPageFinder m_pageFinder`

- `SeqNumChecker m_dungeonConstructChecker`


## Methods

- `Void Render(SandboxV2DungeonZoneViewModel, SandboxV2DungeonViewModel)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2ZoneView : MonoBehaviour, IHotfixable
{
	private UIAtlasImage _imageZoneWeather; // 0x18
	private Image _imageZoneName; // 0x20
	private UIPageFinder m_pageFinder; // 0x28
	private SeqNumChecker m_dungeonConstructChecker; // 0x38
	private static DelegateBridge __Hotfix0_Render; // 0x0
	private static DelegateBridge _c__Hotfix0_ctor; // 0x8


	// RVA: 0x25b1748 VA: 0x7594bc9748
	public Void Render(SandboxV2DungeonZoneViewModel zoneViewModel, SandboxV2DungeonViewModel dungeonViewModel) { }
	// RVA: 0x25b1978 VA: 0x7594bc9978
	public Void .ctor() { }
}
```