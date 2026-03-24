# Renumeração Centesimal do Menu — 0wlops.sh

Cada tática MITRE ATT&CK recebe sua própria centena, eliminando os conflitos de
numeração atual (duplicatas, `aaa`).

## Esquema de Numeração Proposto

| Centena | Tática MITRE | TA# |
|---------|-------------|-----|
| **100** | RECONNAISSANCE | TA0043 |
| **200** | RESOURCE DEVELOPMENT | TA0042 |
| **300** | INITIAL ACCESS | TA0001 |
| **400** | EXECUTION | TA0002 |
| **500** | PERSISTENCE | TA0003 |
| **600** | PRIVILEGE ESCALATION | TA0004 |
| **700** | DEFENSE EVASION | TA0005 |
| **800** | CREDENTIAL ACCESS | TA0006 |
| **900** | DISCOVERY | TA0007 |
| **1000** | LATERAL MOVEMENT | TA0008 |
| **000** | OPERATOR UTILITIES + Exit | — |

## Mapeamento: Opção Atual → Nova Opção

| Módulo (função) | Antiga | Nova | Tática |
|----------------|--------|------|--------|
| [metadata_analysis](file:///home/r3v4n/Documentos/CyberVault/20_PROJECTS/23_EDUCACIONAL/234-PORTFOLIO/owl-ops/0wlops.sh#2472-2757) | 101/103 | **101** | RECONNAISSANCE |
| [whois_dns_recon](file:///home/r3v4n/Documentos/CyberVault/20_PROJECTS/23_EDUCACIONAL/234-PORTFOLIO/owl-ops/0wlops.sh#4106-4210) | 109/102 | **102** | RECONNAISSANCE |
| [rev_dns](file:///home/r3v4n/Documentos/CyberVault/20_PROJECTS/23_EDUCACIONAL/234-PORTFOLIO/owl-ops/0wlops.sh#3554-3639) | 106 | **103** | RECONNAISSANCE |
| [recon_dns](file:///home/r3v4n/Documentos/CyberVault/20_PROJECTS/23_EDUCACIONAL/234-PORTFOLIO/owl-ops/0wlops.sh#3459-3553) | 107 | **104** | RECONNAISSANCE |
| [google_hacking](file:///home/r3v4n/Documentos/CyberVault/20_PROJECTS/23_EDUCACIONAL/234-PORTFOLIO/owl-ops/0wlops.sh#1249-1416) | 102 | **105** | RECONNAISSANCE |
| [parsing_html](file:///home/r3v4n/Documentos/CyberVault/20_PROJECTS/23_EDUCACIONAL/234-PORTFOLIO/owl-ops/0wlops.sh#2976-3131) | 110 | **106** | RECONNAISSANCE |
| [dns_zt](file:///home/r3v4n/Documentos/CyberVault/20_PROJECTS/23_EDUCACIONAL/234-PORTFOLIO/owl-ops/0wlops.sh#807-892) | 104 | **201** | RESOURCE DEVELOPMENT |
| [Subdomain_takeover](file:///home/r3v4n/Documentos/CyberVault/20_PROJECTS/23_EDUCACIONAL/234-PORTFOLIO/owl-ops/0wlops.sh#3830-3917) | 105 | **202** | RESOURCE DEVELOPMENT |
| [wireless_pentest](file:///home/r3v4n/Documentos/CyberVault/20_PROJECTS/23_EDUCACIONAL/234-PORTFOLIO/owl-ops/0wlops.sh#4342-4450) | 500 | **301** | INITIAL ACCESS |
| [portscan](file:///home/r3v4n/Documentos/CyberVault/20_PROJECTS/23_EDUCACIONAL/234-PORTFOLIO/owl-ops/0wlops.sh#3132-3250) | 100 | **901** | DISCOVERY |
| [portscan_bashsocket](file:///home/r3v4n/Documentos/CyberVault/20_PROJECTS/23_EDUCACIONAL/234-PORTFOLIO/owl-ops/0wlops.sh#3251-3365) | aaa | **902** | DISCOVERY |
| [banner_grabber](file:///home/r3v4n/Documentos/CyberVault/20_PROJECTS/23_EDUCACIONAL/234-PORTFOLIO/owl-ops/0wlops.sh#681-806) | 108 | **903** | DISCOVERY |
| [smb_enum](file:///home/r3v4n/Documentos/CyberVault/20_PROJECTS/23_EDUCACIONAL/234-PORTFOLIO/owl-ops/0wlops.sh#3640-3829) | 201 | **904** | DISCOVERY |
| [linux_sysinfo](file:///home/r3v4n/Documentos/CyberVault/20_PROJECTS/23_EDUCACIONAL/234-PORTFOLIO/owl-ops/0wlops.sh#2001-2471) | 203 | **905** | DISCOVERY |
| [find_based_attack_surface_analysis](file:///home/r3v4n/Documentos/CyberVault/20_PROJECTS/23_EDUCACIONAL/234-PORTFOLIO/owl-ops/0wlops.sh#1002-1138) | 300 | **906** | DISCOVERY |
| [find_command_examples](file:///home/r3v4n/Documentos/CyberVault/20_PROJECTS/23_EDUCACIONAL/234-PORTFOLIO/owl-ops/0wlops.sh#1139-1248) | 301 | **907** | DISCOVERY |
| [nmap_network_discovery](file:///home/r3v4n/Documentos/CyberVault/20_PROJECTS/23_EDUCACIONAL/234-PORTFOLIO/owl-ops/0wlops.sh#2898-2975) | 600 | **908** | DISCOVERY |
| [arp_network_scan](file:///home/r3v4n/Documentos/CyberVault/20_PROJECTS/23_EDUCACIONAL/234-PORTFOLIO/owl-ops/0wlops.sh#597-680) | 601 | **909** | DISCOVERY |
| [mitm](file:///home/r3v4n/Documentos/CyberVault/20_PROJECTS/23_EDUCACIONAL/234-PORTFOLIO/owl-ops/0wlops.sh#2758-2897) | 200 | **801** | CREDENTIAL ACCESS |
| [linux_root_password_reset](file:///home/r3v4n/Documentos/CyberVault/20_PROJECTS/23_EDUCACIONAL/234-PORTFOLIO/owl-ops/0wlops.sh#1871-2000) | 302 | **601** | PRIVILEGE ESCALATION |
| [jalesc](file:///home/r3v4n/Documentos/CyberVault/20_PROJECTS/23_EDUCACIONAL/234-PORTFOLIO/owl-ops/0wlops.sh#1417-1870) | 303 | **602** | PRIVILEGE ESCALATION |
| [vim_quick_reference](file:///home/r3v4n/Documentos/CyberVault/20_PROJECTS/23_EDUCACIONAL/234-PORTFOLIO/owl-ops/0wlops.sh#4012-4105) | 400 | **603** | PRIVILEGE ESCALATION |
| [rbash_escape_methods](file:///home/r3v4n/Documentos/CyberVault/20_PROJECTS/23_EDUCACIONAL/234-PORTFOLIO/owl-ops/0wlops.sh#3366-3458) | 401 | **604** | PRIVILEGE ESCALATION |
| `arp_recon_daemon` | 602 | **1001** | LATERAL MOVEMENT |
| [useful_linux_commands](file:///home/r3v4n/Documentos/CyberVault/20_PROJECTS/23_EDUCACIONAL/234-PORTFOLIO/owl-ops/0wlops.sh#3918-4011) | 202 | **001** | OPERATOR UTILITIES |
| [windows_basic_commands](file:///home/r3v4n/Documentos/CyberVault/20_PROJECTS/23_EDUCACIONAL/234-PORTFOLIO/owl-ops/0wlops.sh#4211-4341) | 501 | **002** | OPERATOR UTILITIES |
| [enable_wsl_routing_vbox](file:///home/r3v4n/Documentos/CyberVault/20_PROJECTS/23_EDUCACIONAL/234-PORTFOLIO/owl-ops/0wlops.sh#893-1001) | 1/001 | **003** | OPERATOR UTILITIES |
| [exit_script](file:///home/r3v4n/Documentos/CyberVault/20_PROJECTS/23_EDUCACIONAL/234-PORTFOLIO/owl-ops/0wlops.sh#251-262) | 0/000 | **000** | EXIT |

## Proposed Changes

### 0wlops.sh

#### [MODIFY] [display_numbered_menu_options()](file:///home/r3v4n/Documentos/CyberVault/20_PROJECTS/23_EDUCACIONAL/234-PORTFOLIO/owl-ops/0wlops.sh#378-481)
- Atualizar todos os números `[xxx]` nas linhas echo conforme tabela acima.

#### [MODIFY] [process_menu_option()](file:///home/r3v4n/Documentos/CyberVault/20_PROJECTS/23_EDUCACIONAL/234-PORTFOLIO/owl-ops/0wlops.sh#506-546)
- Atualizar todos os `NNN)` nos cases conforme tabela acima.
- Corrigir `aaa)` → `902)`.
- Corrigir duplicata `102)` para [whois_dns_recon](file:///home/r3v4n/Documentos/CyberVault/20_PROJECTS/23_EDUCACIONAL/234-PORTFOLIO/owl-ops/0wlops.sh#4106-4210).
- Adicionar seção `#* [+] LATERAL MOVEMENT / INTERNAL RECON` com `1001)`.

#### [MODIFY] [validate_input()](file:///home/r3v4n/Documentos/CyberVault/20_PROJECTS/23_EDUCACIONAL/234-PORTFOLIO/owl-ops/0wlops.sh#547-566)
- Atualizar os ranges `seq` para refletir a nova numeração:
  - `seq 1 3` → OPERATOR UTILITIES  
  - `seq 101 106` → RECONNAISSANCE  
  - `seq 201 202` → RESOURCE DEVELOPMENT  
  - `seq 301 301` → INITIAL ACCESS  
  - `seq 601 604` → PRIVILEGE ESCALATION  
  - `seq 801 801` → CREDENTIAL ACCESS  
  - `seq 901 909` → DISCOVERY  
  - `seq 1001 1001` → LATERAL MOVEMENT  

## Verification Plan

### Manual Verification
1. Executar `bash -n 0wlops.sh` para checar erros de sintaxe.
2. Executar [./0wlops.sh](file:///home/r3v4n/Documentos/CyberVault/20_PROJECTS/23_EDUCACIONAL/234-PORTFOLIO/owl-ops/0wlops.sh) e confirmar que o menu exibe os números novos.
3. Testar Fast Mode: `./0wlops.sh 101` deve abrir Metadata Analysis.
4. Testar opção inválida: `./0wlops.sh 999` deve exibir mensagem de erro.
