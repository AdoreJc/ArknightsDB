# MailItemViewModel

**Namespace:** `Torappu.UI.Home`


## Fields

- `Int64 mailId`

- `String fromName`

- `Sprite avatarSprite`

- `DateTime createTime`

- `DateTime receiveTime`

- `DateTime expireTime`

- `String mailTitle`

- `String content`

- `Boolean isReceived`

- `MailFromInfo type`

- `MailStyle style`

- `IPlugin plugin`

- `Boolean m_isSpecialMail`


## Properties

- `Boolean isSpecialMail`


## Methods

- `Boolean get_isSpecialMail()`

- `HomeMailIndex GetIndexId()`

- `Void LoadSurveyViewModel(SurveyItem)`

- `Void LoadViewModel(MailItem, Boolean)`


## Dump
```C#
// Dll : Assembly-CSharp.dll
// Namespace : Torappu.UI.Home
public class MailItemViewModel
{
	public Int64 mailId; // 0x10
	public List`1 gains; // 0x18
	public String fromName; // 0x20
	public Sprite avatarSprite; // 0x28
	public DateTime createTime; // 0x30
	public DateTime receiveTime; // 0x38
	public DateTime expireTime; // 0x40
	public String mailTitle; // 0x48
	public String content; // 0x50
	public Boolean isReceived; // 0x58
	public MailFromInfo type; // 0x5c
	public MailStyle style; // 0x60
	public IPlugin plugin; // 0x68
	private Boolean m_isSpecialMail; // 0x70

	public Boolean isSpecialMail { get; }

	// RVA: 0x281f8dc VA: 0x7594e378dc
	public Boolean get_isSpecialMail() { }
	// RVA: 0x281f91c VA: 0x7594e3791c
	public HomeMailIndex GetIndexId() { }
	// RVA: 0x281f154 VA: 0x7594e37154
	public Void LoadSurveyViewModel(SurveyItem surveyItem) { }
	// RVA: 0x281f314 VA: 0x7594e37314
	public Void LoadViewModel(MailItem serviceModel, Boolean hasItem) { }
	// RVA: 0x281f14c VA: 0x7594e3714c
	public Void .ctor() { }
}
```