# CommonFriendAssistStateBean

**Namespace:** `Torappu.UI.CommonFriendAssist`


## Fields

- `CommonFriendAssistViewModelProperty property`

- `Boolean <chooseAssistSuc>k__BackingField`

- `ICommonFriendAssistPlugin <plugin>k__BackingField`


## Properties

- `Boolean chooseAssistSuc`

- `ICommonFriendAssistPlugin plugin`


## Methods

- `Boolean get_chooseAssistSuc()`

- `Void set_chooseAssistSuc(Boolean)`

- `ICommonFriendAssistPlugin get_plugin()`

- `Void set_plugin(ICommonFriendAssistPlugin)`

- `Void SetPlugin(ICommonFriendAssistPlugin)`

- `Void SetAssistSuc(Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.CommonFriendAssist
public class CommonFriendAssistStateBean : IStateBean, IHotfixable
{
	public static List`1 PROFESSION_LIST; // 0x0
	public CommonFriendAssistViewModelProperty property; // 0x10
	private Boolean <chooseAssistSuc>k__BackingField; // 0x18
	private ICommonFriendAssistPlugin <plugin>k__BackingField; // 0x20
	private static DelegateBridge __Hotfix0_get_chooseAssistSuc; // 0x8
	private static DelegateBridge __Hotfix0_set_chooseAssistSuc; // 0x10
	private static DelegateBridge __Hotfix0_get_plugin; // 0x18
	private static DelegateBridge __Hotfix0_set_plugin; // 0x20
	private static DelegateBridge __Hotfix0_SetPlugin; // 0x28
	private static DelegateBridge __Hotfix0_SetAssistSuc; // 0x30
	private static DelegateBridge _c__Hotfix0_ctor; // 0x38

	public Boolean chooseAssistSuc { get; set; }
	public ICommonFriendAssistPlugin plugin { get; set; }

	// RVA: 0x2c4a524 VA: 0x7595262524
	public Boolean get_chooseAssistSuc() { }
	// RVA: 0x2c4a59c VA: 0x759526259c
	private Void set_chooseAssistSuc(Boolean value) { }
	// RVA: 0x2c49410 VA: 0x7595261410
	public ICommonFriendAssistPlugin get_plugin() { }
	// RVA: 0x2c4a62c VA: 0x759526262c
	private Void set_plugin(ICommonFriendAssistPlugin value) { }
	// RVA: 0x2c4a6c0 VA: 0x75952626c0
	public Void SetPlugin(ICommonFriendAssistPlugin aPlugin) { }
	// RVA: 0x2c49160 VA: 0x7595261160
	public Void SetAssistSuc(Boolean suc) { }
	// RVA: 0x2c4a444 VA: 0x7595262444
	public Void .ctor() { }
	// RVA: 0x2c4a7bc VA: 0x75952627bc
	private static Void .cctor() { }
}
```