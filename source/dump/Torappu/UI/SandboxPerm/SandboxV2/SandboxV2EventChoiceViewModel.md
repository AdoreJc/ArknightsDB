# SandboxV2EventChoiceViewModel

**Namespace:** `Torappu.UI.SandboxPerm.SandboxV2`


## Fields

- `String m_choiceId`

- `String m_title`

- `String m_desc`

- `String m_expeditionId`

- `Int32 m_expeditionDuration`

- `Int32 m_expeditionCharCount`

- `SandboxV2EventChoiceType m_type`

- `Int32 m_costAction`

- `Boolean m_enoughAction`

- `Boolean m_needAction`


## Properties

- `String choiceId`

- `String title`

- `String desc`

- `String expeditionId`

- `Int32 expeditionDuration`

- `Int32 expeditionCharCount`

- `SandboxV2EventChoiceType type`

- `Int32 costAction`

- `Boolean enoughAction`

- `Boolean needAction`


## Methods

- `String get_choiceId()`

- `String get_title()`

- `String get_desc()`

- `String get_expeditionId()`

- `Int32 get_expeditionDuration()`

- `Int32 get_expeditionCharCount()`

- `SandboxV2EventChoiceType get_type()`

- `Int32 get_costAction()`

- `Boolean get_enoughAction()`

- `Boolean get_needAction()`

- `Void LoadData(SandboxV2Data, SandboxV2EventChoiceData, Int32)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.SandboxPerm.SandboxV2
public class SandboxV2EventChoiceViewModel : IHotfixable
{
	private String m_choiceId; // 0x10
	private String m_title; // 0x18
	private String m_desc; // 0x20
	private String m_expeditionId; // 0x28
	private Int32 m_expeditionDuration; // 0x30
	private Int32 m_expeditionCharCount; // 0x34
	private SandboxV2EventChoiceType m_type; // 0x38
	private Int32 m_costAction; // 0x3c
	private Boolean m_enoughAction; // 0x40
	private Boolean m_needAction; // 0x41
	private static DelegateBridge __Hotfix0_get_choiceId; // 0x0
	private static DelegateBridge __Hotfix0_get_title; // 0x8
	private static DelegateBridge __Hotfix0_get_desc; // 0x10
	private static DelegateBridge __Hotfix0_get_expeditionId; // 0x18
	private static DelegateBridge __Hotfix0_get_expeditionDuration; // 0x20
	private static DelegateBridge __Hotfix0_get_expeditionCharCount; // 0x28
	private static DelegateBridge __Hotfix0_get_type; // 0x30
	private static DelegateBridge __Hotfix0_get_costAction; // 0x38
	private static DelegateBridge __Hotfix0_get_enoughAction; // 0x40
	private static DelegateBridge __Hotfix0_get_needAction; // 0x48
	private static DelegateBridge __Hotfix0_LoadData; // 0x50
	private static DelegateBridge _c__Hotfix0_ctor; // 0x58

	public String choiceId { get; }
	public String title { get; }
	public String desc { get; }
	public String expeditionId { get; }
	public Int32 expeditionDuration { get; }
	public Int32 expeditionCharCount { get; }
	public SandboxV2EventChoiceType type { get; }
	public Int32 costAction { get; }
	public Boolean enoughAction { get; }
	public Boolean needAction { get; }

	// RVA: 0x25c7104 VA: 0x7594bdf104
	public String get_choiceId() { }
	// RVA: 0x25c716c VA: 0x7594bdf16c
	public String get_title() { }
	// RVA: 0x25c71d4 VA: 0x7594bdf1d4
	public String get_desc() { }
	// RVA: 0x25c723c VA: 0x7594bdf23c
	public String get_expeditionId() { }
	// RVA: 0x25c72a4 VA: 0x7594bdf2a4
	public Int32 get_expeditionDuration() { }
	// RVA: 0x25c730c VA: 0x7594bdf30c
	public Int32 get_expeditionCharCount() { }
	// RVA: 0x25c7374 VA: 0x7594bdf374
	public SandboxV2EventChoiceType get_type() { }
	// RVA: 0x25c73dc VA: 0x7594bdf3dc
	public Int32 get_costAction() { }
	// RVA: 0x25c7444 VA: 0x7594bdf444
	public Boolean get_enoughAction() { }
	// RVA: 0x25c74ac VA: 0x7594bdf4ac
	public Boolean get_needAction() { }
	// RVA: 0x25c7514 VA: 0x7594bdf514
	public Void LoadData(SandboxV2Data sandboxData, SandboxV2EventChoiceData choiceData, Int32 playerAp) { }
	// RVA: 0x25c7678 VA: 0x7594bdf678
	public Void .ctor() { }
}
```