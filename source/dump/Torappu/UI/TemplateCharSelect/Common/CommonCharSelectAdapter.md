# CommonCharSelectAdapter

**Namespace:** `Torappu.UI.TemplateCharSelect.Common`


## Fields

- `CommonCharSelectCharHolder _holderPrefab`

- `UIIntEvent _charClick`

- `UInt32 _asyncCostPerFrame`

- `Boolean isSingle`

- `TemplateCharSelectCardView <charCardPrefab>k__BackingField`

- `AsyncGameObjectLoader m_viewLoader`


## Properties

- `TemplateCharSelectCardView charCardPrefab`


## Methods

- `TemplateCharSelectCardView get_charCardPrefab()`

- `Void set_charCardPrefab(TemplateCharSelectCardView)`

- `Int32 _GetInstIndex(Int32)`

- `Void Update()`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.TemplateCharSelect.Common
public class CommonCharSelectAdapter : LoopScrollAdapter`2
{
	private CommonCharSelectCharHolder _holderPrefab; // 0x58
	private UIIntEvent _charClick; // 0x60
	private UInt32 _asyncCostPerFrame; // 0x68
	public List`1 selectInstIdList; // 0x70
	public Boolean isSingle; // 0x78
	private TemplateCharSelectCardView <charCardPrefab>k__BackingField; // 0x80
	private AsyncGameObjectLoader m_viewLoader; // 0x88
	private static DelegateBridge __Hotfix0_get_charCardPrefab; // 0x0
	private static DelegateBridge __Hotfix0_set_charCardPrefab; // 0x8
	private static DelegateBridge __Hotfix0__GetInstIndex; // 0x10
	private static DelegateBridge __Hotfix0_CreateView; // 0x18
	private static DelegateBridge __Hotfix0_UpdateView; // 0x20
	private static DelegateBridge __Hotfix0_Update; // 0x28
	private static DelegateBridge _c__Hotfix0_ctor; // 0x30

	public TemplateCharSelectCardView charCardPrefab { get; set; }

	// RVA: 0x2c56d7c VA: 0x759526ed7c
	public TemplateCharSelectCardView get_charCardPrefab() { }
	// RVA: 0x2c56de4 VA: 0x759526ede4
	public Void set_charCardPrefab(TemplateCharSelectCardView value) { }
	// RVA: 0x2c56e68 VA: 0x759526ee68
	private Int32 _GetInstIndex(Int32 instId) { }
	// RVA: 0x2c56f7c VA: 0x759526ef7c
	public override GameObject CreateView(Transform parent) { }
	// RVA: 0x2c5704c VA: 0x759526f04c
	public override Void UpdateView(Int32 position, GameObject view, ViewHolder holder, TemplateCharSelectCardViewModel data) { }
	// RVA: 0x2c574b8 VA: 0x759526f4b8
	private Void Update() { }
	// RVA: 0x2c57534 VA: 0x759526f534
	public Void .ctor() { }
}
```