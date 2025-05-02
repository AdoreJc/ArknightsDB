# SiracusaMapStagePreviewView

**Namespace:** `Torappu.UI.SiracusaMap`


## Fields

- `TemplateActivityMapPreviewView _stagePreviewView`

- `CanvasGroup _stagePreviewCanvasGroup`

- `UISwitchTween m_previewFadeTween`


## Properties

- `TemplateActivityMapPreviewView view`

- `UISwitchTween previewFadeTween`


## Methods

- `TemplateActivityMapPreviewView get_view()`

- `UISwitchTween get_previewFadeTween()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SiracusaMap
public class SiracusaMapStagePreviewView : DataBinder`1
{
	private TemplateActivityMapPreviewView _stagePreviewView; // 0x20
	private CanvasGroup _stagePreviewCanvasGroup; // 0x28
	private UISwitchTween m_previewFadeTween; // 0x30
	private static DelegateBridge __Hotfix0_get_view; // 0x0
	private static DelegateBridge __Hotfix0_get_previewFadeTween; // 0x8
	private static DelegateBridge __Hotfix0_OnValueChanged; // 0x10
	private static DelegateBridge _c__Hotfix0_ctor; // 0x18

	public TemplateActivityMapPreviewView view { get; }
	private UISwitchTween previewFadeTween { get; }

	// RVA: 0x23e3784 VA: 0x75949fb784
	public TemplateActivityMapPreviewView get_view() { }
	// RVA: 0x23e37ec VA: 0x75949fb7ec
	private UISwitchTween get_previewFadeTween() { }
	// RVA: 0x23e38c8 VA: 0x75949fb8c8
	public override Void OnValueChanged(SiracusaMapPanelMapProperty property) { }
	// RVA: 0x23e3a5c VA: 0x75949fba5c
	public Void .ctor() { }
}
```