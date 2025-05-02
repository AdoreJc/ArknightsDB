# unitytls_interface_struct

**Namespace:** ` `


## Fields

- `unitytls_errorstate_create_t unitytls_errorstate_create`

- `unitytls_errorstate_raise_error_t unitytls_errorstate_raise_error`

- `unitytls_key_get_ref_t unitytls_key_get_ref`

- `unitytls_key_parse_der_t unitytls_key_parse_der`

- `unitytls_key_parse_pem_t unitytls_key_parse_pem`

- `unitytls_key_free_t unitytls_key_free`

- `unitytls_x509_export_der_t unitytls_x509_export_der`

- `unitytls_x509list_get_ref_t unitytls_x509list_get_ref`

- `unitytls_x509list_get_x509_t unitytls_x509list_get_x509`

- `unitytls_x509list_create_t unitytls_x509list_create`

- `unitytls_x509list_append_t unitytls_x509list_append`

- `unitytls_x509list_append_der_t unitytls_x509list_append_der`

- `unitytls_x509list_append_der_t unitytls_x509list_append_pem`

- `unitytls_x509list_free_t unitytls_x509list_free`

- `unitytls_x509verify_default_ca_t unitytls_x509verify_default_ca`

- `unitytls_x509verify_explicit_ca_t unitytls_x509verify_explicit_ca`

- `unitytls_tlsctx_create_server_t unitytls_tlsctx_create_server`

- `unitytls_tlsctx_create_client_t unitytls_tlsctx_create_client`

- `unitytls_tlsctx_server_require_client_authentication_t unitytls_tlsctx_server_require_client_authentication`

- `unitytls_tlsctx_set_certificate_callback_t unitytls_tlsctx_set_certificate_callback`

- `unitytls_tlsctx_set_trace_callback_t unitytls_tlsctx_set_trace_callback`

- `unitytls_tlsctx_set_x509verify_callback_t unitytls_tlsctx_set_x509verify_callback`

- `unitytls_tlsctx_set_supported_ciphersuites_t unitytls_tlsctx_set_supported_ciphersuites`

- `unitytls_tlsctx_get_ciphersuite_t unitytls_tlsctx_get_ciphersuite`

- `unitytls_tlsctx_get_protocol_t unitytls_tlsctx_get_protocol`

- `unitytls_tlsctx_process_handshake_t unitytls_tlsctx_process_handshake`

- `unitytls_tlsctx_read_t unitytls_tlsctx_read`

- `unitytls_tlsctx_write_t unitytls_tlsctx_write`

- `unitytls_tlsctx_notify_close_t unitytls_tlsctx_notify_close`

- `unitytls_tlsctx_free_t unitytls_tlsctx_free`

- `unitytls_random_generate_bytes_t unitytls_random_generate_bytes`


## Dump
```C#
// Dll : System.dll
// Namespace : 
public class unitytls_interface_struct
{
	public readonly UInt64 UNITYTLS_INVALID_HANDLE; // 0x10
	public readonly unitytls_tlsctx_protocolrange UNITYTLS_TLSCTX_PROTOCOLRANGE_DEFAULT; // 0x18
	public unitytls_errorstate_create_t unitytls_errorstate_create; // 0x20
	public unitytls_errorstate_raise_error_t unitytls_errorstate_raise_error; // 0x28
	public unitytls_key_get_ref_t unitytls_key_get_ref; // 0x30
	public unitytls_key_parse_der_t unitytls_key_parse_der; // 0x38
	public unitytls_key_parse_pem_t unitytls_key_parse_pem; // 0x40
	public unitytls_key_free_t unitytls_key_free; // 0x48
	public unitytls_x509_export_der_t unitytls_x509_export_der; // 0x50
	public unitytls_x509list_get_ref_t unitytls_x509list_get_ref; // 0x58
	public unitytls_x509list_get_x509_t unitytls_x509list_get_x509; // 0x60
	public unitytls_x509list_create_t unitytls_x509list_create; // 0x68
	public unitytls_x509list_append_t unitytls_x509list_append; // 0x70
	public unitytls_x509list_append_der_t unitytls_x509list_append_der; // 0x78
	public unitytls_x509list_append_der_t unitytls_x509list_append_pem; // 0x80
	public unitytls_x509list_free_t unitytls_x509list_free; // 0x88
	public unitytls_x509verify_default_ca_t unitytls_x509verify_default_ca; // 0x90
	public unitytls_x509verify_explicit_ca_t unitytls_x509verify_explicit_ca; // 0x98
	public unitytls_tlsctx_create_server_t unitytls_tlsctx_create_server; // 0xa0
	public unitytls_tlsctx_create_client_t unitytls_tlsctx_create_client; // 0xa8
	public unitytls_tlsctx_server_require_client_authentication_t unitytls_tlsctx_server_require_client_authentication; // 0xb0
	public unitytls_tlsctx_set_certificate_callback_t unitytls_tlsctx_set_certificate_callback; // 0xb8
	public unitytls_tlsctx_set_trace_callback_t unitytls_tlsctx_set_trace_callback; // 0xc0
	public unitytls_tlsctx_set_x509verify_callback_t unitytls_tlsctx_set_x509verify_callback; // 0xc8
	public unitytls_tlsctx_set_supported_ciphersuites_t unitytls_tlsctx_set_supported_ciphersuites; // 0xd0
	public unitytls_tlsctx_get_ciphersuite_t unitytls_tlsctx_get_ciphersuite; // 0xd8
	public unitytls_tlsctx_get_protocol_t unitytls_tlsctx_get_protocol; // 0xe0
	public unitytls_tlsctx_process_handshake_t unitytls_tlsctx_process_handshake; // 0xe8
	public unitytls_tlsctx_read_t unitytls_tlsctx_read; // 0xf0
	public unitytls_tlsctx_write_t unitytls_tlsctx_write; // 0xf8
	public unitytls_tlsctx_notify_close_t unitytls_tlsctx_notify_close; // 0x100
	public unitytls_tlsctx_free_t unitytls_tlsctx_free; // 0x108
	public unitytls_random_generate_bytes_t unitytls_random_generate_bytes; // 0x110


	// RVA: 0x6253c54 VA: 0x759886bc54
	public Void .ctor() { }
}
```