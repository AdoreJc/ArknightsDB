# CommonCharSelectResHolder

**Namespace:** `Torappu.UI.TemplateCharSelect.Common`


## Fields

- `TemplateCharSelectCardView _charCard`

- `TemplateCharSelectPoolView _poolView`

- `TemplateCharSelectDetailView _detailView`

- `TemplateCharSelectShuffleView _shuffleView`

- `TemplateCharSelectEnsureView _ensureView`


## Properties

- `TemplateCharSelectCardView charCard`

- `TemplateCharSelectPoolView poolView`

- `TemplateCharSelectDetailView detailView`

- `TemplateCharSelectShuffleView shuffleView`

- `TemplateCharSelectEnsureView ensureView`


## Methods

- `TemplateCharSelectCardView get_charCard()`

- `TemplateCharSelectPoolView get_poolView()`

- `TemplateCharSelectDetailView get_detailView()`

- `TemplateCharSelectShuffleView get_shuffleView()`

- `TemplateCharSelectEnsureView get_ensureView()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.TemplateCharSelect.Common
public class CommonCharSelectResHolder : MonoBehaviour, ITemplateCharSelectCustomization, IHotfixable
{
	private TemplateCharSelectCardView _charCard; // 0x18
	private TemplateCharSelectPoolView _poolView; // 0x20
	private TemplateCharSelectDetailView _detailView; // 0x28
	private TemplateCharSelectShuffleView _shuffleView; // 0x30
	private TemplateCharSelectEnsureView _ensureView; // 0x38
	private static DelegateBridge __Hotfix0_get_charCard; // 0x0
	private static DelegateBridge __Hotfix0_get_poolView; // 0x8
	private static DelegateBridge __Hotfix0_get_detailView; // 0x10
	private static DelegateBridge __Hotfix0_get_shuffleView; // 0x18
	private static DelegateBridge __Hotfix0_get_ensureView; // 0x20
	private static DelegateBridge __Hotfix0_get_extraViews; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public TemplateCharSelectCardView charCard { get; }
	public TemplateCharSelectPoolView poolView { get; }
	public TemplateCharSelectDetailView detailView { get; }
	public TemplateCharSelectShuffleView shuffleView { get; }
	public TemplateCharSelectEnsureView ensureView { get; }
	public IList`1 extraViews { get; }

	// RVA: 0x2c4fff4 VA: 0x7595267ff4
	public TemplateCharSelectCardView get_charCard() { }
	// RVA: 0x2c5005c VA: 0x759526805c
	public TemplateCharSelectPoolView get_poolView() { }
	// RVA: 0x2c500c4 VA: 0x75952680c4
	public TemplateCharSelectDetailView get_detailView() { }
	// RVA: 0x2c5012c VA: 0x759526812c
	public TemplateCharSelectShuffleView get_shuffleView() { }
	// RVA: 0x2c50194 VA: 0x7595268194
	public TemplateCharSelectEnsureView get_ensureView() { }
	// RVA: 0x2c5acf0 VA: 0x7595272cf0
	public IList`1 get_extraViews() { }
	// RVA: 0x2c5ad54 VA: 0x7595272d54
	public Void .ctor() { }
}
```