# TuningCommonCard

**Namespace:** `Torappu.UI.Tuning`


## Fields

- `Image _cardImg`

- `Image _orcheImg`

- `GameObject _fragmentGroupObj`

- `UIPageFinder m_pageFinder`


## Methods

- `Void RenderCard(TuningCommonCardModel)`

- `Void SetScaler(Single)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Tuning
public class TuningCommonCard : MonoBehaviour, IHotfixable
{
	private Image _cardImg; // 0x18
	private Image _orcheImg; // 0x20
	private List`1 _fragmentImgList; // 0x28
	private GameObject _fragmentGroupObj; // 0x30
	private UIPageFinder m_pageFinder; // 0x38
	private static DelegateBridge __Hotfix0_RenderCard; // 0x0
	private static DelegateBridge __Hotfix0_SetScaler; // 0x8
	private static DelegateBridge _c__Hotfix0_ctor; // 0x10


	// RVA: 0x2318fc8 VA: 0x7594930fc8
	public Void RenderCard(TuningCommonCardModel cardModel) { }
	// RVA: 0x23192d8 VA: 0x75949312d8
	public Void SetScaler(Single scaler) { }
	// RVA: 0x2321400 VA: 0x7594939400
	public Void .ctor() { }
}
```