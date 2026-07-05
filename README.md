# 00007FF71E2A2586 code around 
00007FF71E2A2327 | 41:57                    | push r15                                | r15:GetMessageW
00007FF71E2A2329 | 41:56                    | push r14                                |
00007FF71E2A232B | 41:55                    | push r13                                | r13:DispatchMessageW
00007FF71E2A232D | 41:54                    | push r12                                | r12:TranslateMessage
00007FF71E2A232F | 56                       | push rsi                                |
00007FF71E2A2330 | 57                       | push rdi                                |
00007FF71E2A2331 | 55                       | push rbp                                |
00007FF71E2A2332 | 53                       | push rbx                                |
00007FF71E2A2333 | B8 F8990000              | mov eax,99F8                            |
00007FF71E2A2338 | E8 B3761500              | call <tauri-app.sub_7FF71E3F99F0>       |
00007FF71E2A233D | 48:29C4                  | sub rsp,rax                             |
00007FF71E2A2340 | 48:89D3                  | mov rbx,rdx                             |
00007FF71E2A2343 | 48:8BB2 D0010000         | mov rsi,qword ptr ds:[rdx+1D0]          |
00007FF71E2A234A | 48:8BBA D8010000         | mov rdi,qword ptr ds:[rdx+1D8]          |
00007FF71E2A2351 | 4C:8D05 80B42B00         | lea r8,qword ptr ds:[7FF71E55D7D8]      | 00007FF71E55D7D8:"get_connectionsexecute_scriptrefresh_access_token_commandcomplete_token_refreshfail_token_refreshcomplete_session_token_responseread_fileread_file_base64write_filerename_filedelete_filecopy_filefile_existsopen_file_dialogsave_file_dialogopen_theme_file_dialogopen_theme_media_file_dialogsave_theme_file_dialogsave_file_to_scriptscreate_directorydirectory_existsdelete_directoryrename_directorylist_files_in_directorylist_directory_entriesget_scripts_directory_cmdget_autoexec_directory_cmdget
00007FF71E2A2358 | 41:B9 0F000000           | mov r9d,F                               |
00007FF71E2A235E | 48:89F1                  | mov rcx,rsi                             |
00007FF71E2A2361 | 48:89FA                  | mov rdx,rdi                             |
00007FF71E2A2364 | E8 FC22C8FF              | call <tauri-app.sub_7FF71DF24665>       |
00007FF71E2A2369 | 84C0                     | test al,al                              |
00007FF71E2A236B | 0F84 DF000000            | je tauri-app.7FF71E2A2450               |
00007FF71E2A2371 | 48:8D83 08020000         | lea rax,qword ptr ds:[rbx+208]          |
00007FF71E2A2378 | 4C:8B8B 88030000         | mov r9,qword ptr ds:[rbx+388]           |
00007FF71E2A237F | 4C:8B93 90030000         | mov r10,qword ptr ds:[rbx+390]          |
00007FF71E2A2386 | 48:8B8B A8030000         | mov rcx,qword ptr ds:[rbx+3A8]          |
00007FF71E2A238D | 48:8D9424 206A0000       | lea rdx,qword ptr ss:[rsp+6A20]         |
00007FF71E2A2395 | 48:898A 18020000         | mov qword ptr ds:[rdx+218],rcx          |
00007FF71E2A239C | 0F1083 98030000          | movups xmm0,xmmword ptr ds:[rbx+398]    |
00007FF71E2A23A3 | 0F1182 08020000          | movups xmmword ptr ds:[rdx+208],xmm0    |
00007FF71E2A23AA | B9 08020000              | mov ecx,208                             |
00007FF71E2A23AF | 48:89D7                  | mov rdi,rdx                             |
00007FF71E2A23B2 | 48:89DE                  | mov rsi,rbx                             |
00007FF71E2A23B5 | F3:A4                    | rep movsb                               |
00007FF71E2A23B7 | 4C:8D8424 580A0000       | lea r8,qword ptr ss:[rsp+A58]           |
00007FF71E2A23BF | B9 D8030000              | mov ecx,3D8                             |
00007FF71E2A23C4 | 4C:89C7                  | mov rdi,r8                              |
00007FF71E2A23C7 | 48:89D6                  | mov rsi,rdx                             |
00007FF71E2A23CA | F3:A4                    | rep movsb                               |
00007FF71E2A23CC | 45:31DB                  | xor r11d,r11d                           |
00007FF71E2A23CF | 45:8898 D8030000         | mov byte ptr ds:[r8+3D8],r11b           |
00007FF71E2A23D6 | 48:8D9424 D0080000       | lea rdx,qword ptr ss:[rsp+8D0]          |
00007FF71E2A23DE | B9 68010000              | mov ecx,168                             |
00007FF71E2A23E3 | 48:89D7                  | mov rdi,rdx                             |
00007FF71E2A23E6 | 48:89C6                  | mov rsi,rax                             |
00007FF71E2A23E9 | F3:A4                    | rep movsb                               |
00007FF71E2A23EB | 4D:8948 F8               | mov qword ptr ds:[r8-8],r9              |
00007FF71E2A23EF | 0F1083 70030000          | movups xmm0,xmmword ptr ds:[rbx+370]    |
00007FF71E2A23F6 | 41:0F1140 E0             | movups xmmword ptr ds:[r8-20],xmm0      |
00007FF71E2A23FB | 48:8B83 80030000         | mov rax,qword ptr ds:[rbx+380]          |
00007FF71E2A2402 | 49:8940 F0               | mov qword ptr ds:[r8-10],rax            |
00007FF71E2A2406 | 4C:8992 48090000         | mov qword ptr ds:[rdx+948],r10          |
00007FF71E2A240D | 44:889A 50090000         | mov byte ptr ds:[rdx+950],r11b          |
00007FF71E2A2414 | E8 6672E8FF              | call tauri-app.7FF71E12967F             |
00007FF71E2A2419 | 833D 80527A00 02         | cmp dword ptr ds:[7FF71EA476A0],2       |
00007FF71E2A2420 | 0F85 29010000            | jne tauri-app.7FF71E2A254F              |
00007FF71E2A2426 | 48:8B15 63527A00         | mov rdx,qword ptr ds:[7FF71EA47690]     |
00007FF71E2A242D | 4C:8B05 64527A00         | mov r8,qword ptr ds:[7FF71EA47698]      |
00007FF71E2A2434 | 48:8DBC24 30010000       | lea rdi,qword ptr ss:[rsp+130]          | [rsp+130]:sub_7FF71E191E83+5C
00007FF71E2A243C | 48:89F9                  | mov rcx,rdi                             |
00007FF71E2A243F | E8 725D0B00              | call <tauri-app.sub_7FF71E3581B6>       |
00007FF71E2A2444 | 48:8D15 45587000         | lea rdx,qword ptr ds:[7FF71E9A7C90]     | 00007FF71E9A7C90:&"/build\\source\\repos\\volt\\volt-monorepo\\apps\\desktop-interface\\.cargo-home\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tauri-2.9.2\\src\\async_runtime.rs"
00007FF71E2A244B | E9 24010000              | jmp tauri-app.7FF71E2A2574              |
00007FF71E2A2450 | 4C:8D05 90B32B00         | lea r8,qword ptr ds:[7FF71E55D7E7]      | 00007FF71E55D7E7:"execute_scriptrefresh_access_token_commandcomplete_token_refreshfail_token_refreshcomplete_session_token_responseread_fileread_file_base64write_filerename_filedelete_filecopy_filefile_existsopen_file_dialogsave_file_dialogopen_theme_file_dialogopen_theme_media_file_dialogsave_theme_file_dialogsave_file_to_scriptscreate_directorydirectory_existsdelete_directoryrename_directorylist_files_in_directorylist_directory_entriesget_scripts_directory_cmdget_autoexec_directory_cmdget_workspace_dire
00007FF71E2A2457 | 41:B9 0E000000           | mov r9d,E                               |
00007FF71E2A245D | 48:89F1                  | mov rcx,rsi                             |
00007FF71E2A2460 | 48:89FA                  | mov rdx,rdi                             |
00007FF71E2A2463 | E8 FD21C8FF              | call <tauri-app.sub_7FF71DF24665>       |
00007FF71E2A2468 | 84C0                     | test al,al                              |
00007FF71E2A246A | 0F84 16010000            | je tauri-app.7FF71E2A2586               |
00007FF71E2A2470 | 48:8D83 08020000         | lea rax,qword ptr ds:[rbx+208]          |
00007FF71E2A2477 | 4C:8B8B 88030000         | mov r9,qword ptr ds:[rbx+388]           |
00007FF71E2A247E | 4C:8B93 90030000         | mov r10,qword ptr ds:[rbx+390]          |
00007FF71E2A2485 | 48:8B8B A8030000         | mov rcx,qword ptr ds:[rbx+3A8]          |
00007FF71E2A248C | 48:8D9424 206A0000       | lea rdx,qword ptr ss:[rsp+6A20]         |
00007FF71E2A2494 | 48:898A 18020000         | mov qword ptr ds:[rdx+218],rcx          |
00007FF71E2A249B | 0F1083 98030000          | movups xmm0,xmmword ptr ds:[rbx+398]    |
00007FF71E2A24A2 | 0F1182 08020000          | movups xmmword ptr ds:[rdx+208],xmm0    |
00007FF71E2A24A9 | B9 08020000              | mov ecx,208                             |
00007FF71E2A24AE | 48:89D7                  | mov rdi,rdx                             |
00007FF71E2A24B1 | 48:89DE                  | mov rsi,rbx                             |
00007FF71E2A24B4 | F3:A4                    | rep movsb                               |
00007FF71E2A24B6 | 4C:8D8424 580A0000       | lea r8,qword ptr ss:[rsp+A58]           |
00007FF71E2A24BE | B9 000F0000              | mov ecx,F00                             |
00007FF71E2A24C3 | 4C:89C7                  | mov rdi,r8                              |
00007FF71E2A24C6 | 48:89D6                  | mov rsi,rdx                             |
00007FF71E2A24C9 | F3:A4                    | rep movsb                               |
00007FF71E2A24CB | 45:31DB                  | xor r11d,r11d                           |
00007FF71E2A24CE | 45:8898 000F0000         | mov byte ptr ds:[r8+F00],r11b           |
00007FF71E2A24D5 | 48:8D9424 D0080000       | lea rdx,qword ptr ss:[rsp+8D0]          |
00007FF71E2A24DD | B9 68010000              | mov ecx,168                             |
00007FF71E2A24E2 | 48:89D7                  | mov rdi,rdx                             |
00007FF71E2A24E5 | 48:89C6                  | mov rsi,rax                             |
00007FF71E2A24E8 | F3:A4                    | rep movsb                               |
00007FF71E2A24EA | 4D:8948 F8               | mov qword ptr ds:[r8-8],r9              |
00007FF71E2A24EE | 0F1083 70030000          | movups xmm0,xmmword ptr ds:[rbx+370]    |
00007FF71E2A24F5 | 41:0F1140 E0             | movups xmmword ptr ds:[r8-20],xmm0      |
00007FF71E2A24FA | 48:8B83 80030000         | mov rax,qword ptr ds:[rbx+380]          |
00007FF71E2A2501 | 49:8940 F0               | mov qword ptr ds:[r8-10],rax            |
00007FF71E2A2505 | 4C:8992 981F0000         | mov qword ptr ds:[rdx+1F98],r10         |
00007FF71E2A250C | 44:889A A01F0000         | mov byte ptr ds:[rdx+1FA0],r11b         |
00007FF71E2A2513 | E8 6771E8FF              | call tauri-app.7FF71E12967F             |
00007FF71E2A2518 | 833D 81517A00 02         | cmp dword ptr ds:[7FF71EA476A0],2       |
00007FF71E2A251F | 0F85 60010000            | jne tauri-app.7FF71E2A2685              |
00007FF71E2A2525 | 48:8B15 64517A00         | mov rdx,qword ptr ds:[7FF71EA47690]     |
00007FF71E2A252C | 4C:8B05 65517A00         | mov r8,qword ptr ds:[7FF71EA47698]      |
00007FF71E2A2533 | 48:8DBC24 30010000       | lea rdi,qword ptr ss:[rsp+130]          | [rsp+130]:sub_7FF71E191E83+5C
00007FF71E2A253B | 48:89F9                  | mov rcx,rdi                             |
00007FF71E2A253E | E8 735C0B00              | call <tauri-app.sub_7FF71E3581B6>       |
00007FF71E2A2543 | 48:8D15 46577000         | lea rdx,qword ptr ds:[7FF71E9A7C90]     | 00007FF71E9A7C90:&"/build\\source\\repos\\volt\\volt-monorepo\\apps\\desktop-interface\\.cargo-home\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tauri-2.9.2\\src\\async_runtime.rs"
00007FF71E2A254A | E9 5B010000              | jmp tauri-app.7FF71E2A26AA              |
00007FF71E2A254F | 48:8B15 7A517A00         | mov rdx,qword ptr ds:[7FF71EA476D0]     |
00007FF71E2A2556 | 4C:8B05 7B517A00         | mov r8,qword ptr ds:[7FF71EA476D8]      |
00007FF71E2A255D | 48:8DBC24 30010000       | lea rdi,qword ptr ss:[rsp+130]          | [rsp+130]:sub_7FF71E191E83+5C
00007FF71E2A2565 | 48:89F9                  | mov rcx,rdi                             |
00007FF71E2A2568 | E8 495C0B00              | call <tauri-app.sub_7FF71E3581B6>       |
00007FF71E2A256D | 48:8D15 34577000         | lea rdx,qword ptr ds:[7FF71E9A7CA8]     | 00007FF71E9A7CA8:&"/build\\source\\repos\\volt\\volt-monorepo\\apps\\desktop-interface\\.cargo-home\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tauri-2.9.2\\src\\async_runtime.rs"
00007FF71E2A2574 | 48:8D8C24 D0080000       | lea rcx,qword ptr ss:[rsp+8D0]          |
00007FF71E2A257C | E8 193F0400              | call <tauri-app.sub_7FF71E2E649A>       |
00007FF71E2A2581 | E9 EF1C0000              | jmp tauri-app.7FF71E2A4275              |
00007FF71E2A2586 | 4C:8D05 68B22B00         | lea r8,qword ptr ds:[7FF71E55D7F5]      | 00007FF71E55D7F5:"refresh_access_token_commandcomplete_token_refreshfail_token_refreshcomplete_session_token_responseread_fileread_file_base64write_filerename_filedelete_filecopy_filefile_existsopen_file_dialogsave_file_dialogopen_theme_file_dialogopen_theme_media_file_dialogsave_theme_file_dialogsave_file_to_scriptscreate_directorydirectory_existsdelete_directoryrename_directorylist_files_in_directorylist_directory_entriesget_scripts_directory_cmdget_autoexec_directory_cmdget_workspace_directory_cmdopen_
00007FF71E2A258D | 41:B9 1C000000           | mov r9d,1C                              |
00007FF71E2A2593 | 48:89F1                  | mov rcx,rsi                             |
00007FF71E2A2596 | 48:89FA                  | mov rdx,rdi                             |
00007FF71E2A2599 | E8 C720C8FF              | call <tauri-app.sub_7FF71DF24665>       |
00007FF71E2A259E | 84C0                     | test al,al                              |
00007FF71E2A25A0 | 0F84 16010000            | je tauri-app.7FF71E2A26BC               |
00007FF71E2A25A6 | 48:8D83 08020000         | lea rax,qword ptr ds:[rbx+208]          |
00007FF71E2A25AD | 4C:8B8B 88030000         | mov r9,qword ptr ds:[rbx+388]           |
00007FF71E2A25B4 | 4C:8B93 90030000         | mov r10,qword ptr ds:[rbx+390]          |
00007FF71E2A25BB | 48:8B8B A8030000         | mov rcx,qword ptr ds:[rbx+3A8]          |
00007FF71E2A25C2 | 48:8D9424 206A0000       | lea rdx,qword ptr ss:[rsp+6A20]         |
00007FF71E2A25CA | 48:898A 18020000         | mov qword ptr ds:[rdx+218],rcx          |
00007FF71E2A25D1 | 0F1083 98030000          | movups xmm0,xmmword ptr ds:[rbx+398]    |
00007FF71E2A25D8 | 0F1182 08020000          | movups xmmword ptr ds:[rdx+208],xmm0    |
00007FF71E2A25DF | B9 08020000              | mov ecx,208                             |
00007FF71E2A25E4 | 48:89D7                  | mov rdi,rdx                             |
00007FF71E2A25E7 | 48:89DE                  | mov rsi,rbx                             |
00007FF71E2A25EA | F3:A4                    | rep movsb                               |
00007FF71E2A25EC | 4C:8D8424 580A0000       | lea r8,qword ptr ss:[rsp+A58]           |
00007FF71E2A25F4 | B9 C8070000              | mov ecx,7C8                             |
00007FF71E2A25F9 | 4C:89C7                  | mov rdi,r8                              |
00007FF71E2A25FC | 48:89D6                  | mov rsi,rdx                             |
00007FF71E2A25FF | F3:A4                    | rep movsb                               |
00007FF71E2A2601 | 45:31DB                  | xor r11d,r11d                           |
00007FF71E2A2604 | 45:8898 C8070000         | mov byte ptr ds:[r8+7C8],r11b           |
00007FF71E2A260B | 48:8D9424 D0080000       | lea rdx,qword ptr ss:[rsp+8D0]          |
00007FF71E2A2613 | B9 68010000              | mov ecx,168                             |
00007FF71E2A2618 | 48:89D7                  | mov rdi,rdx                             |
00007FF71E2A261B | 48:89C6                  | mov rsi,rax                             |
00007FF71E2A261E | F3:A4                    | rep movsb                               |
00007FF71E2A2620 | 4D:8948 F8               | mov qword ptr ds:[r8-8],r9              |
00007FF71E2A2624 | 0F1083 70030000          | movups xmm0,xmmword ptr ds:[rbx+370]    |
00007FF71E2A262B | 41:0F1140 E0             | movups xmmword ptr ds:[r8-20],xmm0      |
00007FF71E2A2630 | 48:8B83 80030000         | mov rax,qword ptr ds:[rbx+380]          |
00007FF71E2A2637 | 49:8940 F0               | mov qword ptr ds:[r8-10],rax            |
00007FF71E2A263B | 4C:8992 28110000         | mov qword ptr ds:[rdx+1128],r10         |
00007FF71E2A2642 | 44:889A 30110000         | mov byte ptr ds:[rdx+1130],r11b         |
00007FF71E2A2649 | E8 3170E8FF              | call tauri-app.7FF71E12967F             |
00007FF71E2A264E | 833D 4B507A00 02         | cmp dword ptr ds:[7FF71EA476A0],2       |
00007FF71E2A2655 | 0F85 60010000            | jne tauri-app.7FF71E2A27BB              |
00007FF71E2A265B | 48:8B15 2E507A00         | mov rdx,qword ptr ds:[7FF71EA47690]     |
00007FF71E2A2662 | 4C:8B05 2F507A00         | mov r8,qword ptr ds:[7FF71EA47698]      |
00007FF71E2A2669 | 48:8DBC24 30010000       | lea rdi,qword ptr ss:[rsp+130]          | [rsp+130]:sub_7FF71E191E83+5C
00007FF71E2A2671 | 48:89F9                  | mov rcx,rdi                             |
00007FF71E2A2674 | E8 3D5B0B00              | call <tauri-app.sub_7FF71E3581B6>       |
00007FF71E2A2679 | 48:8D15 10567000         | lea rdx,qword ptr ds:[7FF71E9A7C90]     | 00007FF71E9A7C90:&"/build\\source\\repos\\volt\\volt-monorepo\\apps\\desktop-interface\\.cargo-home\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tauri-2.9.2\\src\\async_runtime.rs"
00007FF71E2A2680 | E9 5B010000              | jmp tauri-app.7FF71E2A27E0              |
00007FF71E2A2685 | 48:8B15 44507A00         | mov rdx,qword ptr ds:[7FF71EA476D0]     |
00007FF71E2A268C | 4C:8B05 45507A00         | mov r8,qword ptr ds:[7FF71EA476D8]      |
00007FF71E2A2693 | 48:8DBC24 30010000       | lea rdi,qword ptr ss:[rsp+130]          | [rsp+130]:sub_7FF71E191E83+5C
00007FF71E2A269B | 48:89F9                  | mov rcx,rdi                             |
00007FF71E2A269E | E8 135B0B00              | call <tauri-app.sub_7FF71E3581B6>       |
00007FF71E2A26A3 | 48:8D15 FE557000         | lea rdx,qword ptr ds:[7FF71E9A7CA8]     | 00007FF71E9A7CA8:&"/build\\source\\repos\\volt\\volt-monorepo\\apps\\desktop-interface\\.cargo-home\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tauri-2.9.2\\src\\async_runtime.rs"
00007FF71E2A26AA | 48:8D8C24 D0080000       | lea rcx,qword ptr ss:[rsp+8D0]          |
00007FF71E2A26B2 | E8 53180400              | call <tauri-app.sub_7FF71E2E3F0A>       |
00007FF71E2A26B7 | E9 B91B0000              | jmp tauri-app.7FF71E2A4275              |
00007FF71E2A26BC | 4C:8D05 4EB12B00         | lea r8,qword ptr ds:[7FF71E55D811]      | 00007FF71E55D811:"complete_token_refreshfail_token_refreshcomplete_session_token_responseread_fileread_file_base64write_filerename_filedelete_filecopy_filefile_existsopen_file_dialogsave_file_dialogopen_theme_file_dialogopen_theme_media_file_dialogsave_theme_file_dialogsave_file_to_scriptscreate_directorydirectory_existsdelete_directoryrename_directorylist_files_in_directorylist_directory_entriesget_scripts_directory_cmdget_autoexec_directory_cmdget_workspace_directory_cmdopen_folder_in_explorerensure_ign
00007FF71E2A26C3 | 41:B9 16000000           | mov r9d,16                              |
00007FF71E2A26C9 | 48:89F1                  | mov rcx,rsi                             |
00007FF71E2A26CC | 48:89FA                  | mov rdx,rdi                             |
00007FF71E2A26CF | E8 911FC8FF              | call <tauri-app.sub_7FF71DF24665>       |
00007FF71E2A26D4 | 84C0                     | test al,al                              |
00007FF71E2A26D6 | 0F84 16010000            | je tauri-app.7FF71E2A27F2               |
00007FF71E2A26DC | 48:8D83 08020000         | lea rax,qword ptr ds:[rbx+208]          |
00007FF71E2A26E3 | 4C:8B8B 88030000         | mov r9,qword ptr ds:[rbx+388]           |
00007FF71E2A26EA | 4C:8B93 90030000         | mov r10,qword ptr ds:[rbx+390]          |
00007FF71E2A26F1 | 48:8B8B A8030000         | mov rcx,qword ptr ds:[rbx+3A8]          |
00007FF71E2A26F8 | 48:8D9424 206A0000       | lea rdx,qword ptr ss:[rsp+6A20]         |
00007FF71E2A2700 | 48:898A 18020000         | mov qword ptr ds:[rdx+218],rcx          |
00007FF71E2A2707 | 0F1083 98030000          | movups xmm0,xmmword ptr ds:[rbx+398]    |
00007FF71E2A270E | 0F1182 08020000          | movups xmmword ptr ds:[rdx+208],xmm0    |
00007FF71E2A2715 | B9 08020000              | mov ecx,208                             |
00007FF71E2A271A | 48:89D7                  | mov rdi,rdx                             |
00007FF71E2A271D | 48:89DE                  | mov rsi,rbx                             |
00007FF71E2A2720 | F3:A4                    | rep movsb                               |
00007FF71E2A2722 | 4C:8D8424 580A0000       | lea r8,qword ptr ss:[rsp+A58]           |
00007FF71E2A272A | B9 A0020000              | mov ecx,2A0                             |
00007FF71E2A272F | 4C:89C7                  | mov rdi,r8                              |
00007FF71E2A2732 | 48:89D6                  | mov rsi,rdx                             |
00007FF71E2A2735 | F3:A4                    | rep movsb                               |
00007FF71E2A2737 | 45:31DB                  | xor r11d,r11d                           |
00007FF71E2A273A | 45:8898 A0020000         | mov byte ptr ds:[r8+2A0],r11b           |
00007FF71E2A2741 | 48:8D9424 D0080000       | lea rdx,qword ptr ss:[rsp+8D0]          |
00007FF71E2A2749 | B9 68010000              | mov ecx,168                             |
00007FF71E2A274E | 48:89D7                  | mov rdi,rdx                             |
00007FF71E2A2751 | 48:89C6                  | mov rsi,rax                             |
00007FF71E2A2754 | F3:A4                    | rep movsb                               |
00007FF71E2A2756 | 4D:8948 F8               | mov qword ptr ds:[r8-8],r9              |
00007FF71E2A275A | 0F1083 70030000          | movups xmm0,xmmword ptr ds:[rbx+370]    |
00007FF71E2A2761 | 41:0F1140 E0             | movups xmmword ptr ds:[r8-20],xmm0      |
00007FF71E2A2766 | 48:8B83 80030000         | mov rax,qword ptr ds:[rbx+380]          |
00007FF71E2A276D | 49:8940 F0               | mov qword ptr ds:[r8-10],rax            |
00007FF71E2A2771 | 4C:8992 D8060000         | mov qword ptr ds:[rdx+6D8],r10          |
00007FF71E2A2778 | 44:889A E0060000         | mov byte ptr ds:[rdx+6E0],r11b          |
00007FF71E2A277F | E8 FB6EE8FF              | call tauri-app.7FF71E12967F             |
00007FF71E2A2784 | 833D 154F7A00 02         | cmp dword ptr ds:[7FF71EA476A0],2       |
00007FF71E2A278B | 0F85 60010000            | jne tauri-app.7FF71E2A28F1              |
00007FF71E2A2791 | 48:8B15 F84E7A00         | mov rdx,qword ptr ds:[7FF71EA47690]     |
00007FF71E2A2798 | 4C:8B05 F94E7A00         | mov r8,qword ptr ds:[7FF71EA47698]      |
00007FF71E2A279F | 48:8DBC24 30010000       | lea rdi,qword ptr ss:[rsp+130]          | [rsp+130]:sub_7FF71E191E83+5C
00007FF71E2A27A7 | 48:89F9                  | mov rcx,rdi                             |
00007FF71E2A27AA | E8 075A0B00              | call <tauri-app.sub_7FF71E3581B6>       |
00007FF71E2A27AF | 48:8D15 DA547000         | lea rdx,qword ptr ds:[7FF71E9A7C90]     | 00007FF71E9A7C90:&"/build\\source\\repos\\volt\\volt-monorepo\\apps\\desktop-interface\\.cargo-home\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tauri-2.9.2\\src\\async_runtime.rs"
00007FF71E2A27B6 | E9 5B010000              | jmp tauri-app.7FF71E2A2916              |
00007FF71E2A27BB | 48:8B15 0E4F7A00         | mov rdx,qword ptr ds:[7FF71EA476D0]     |
00007FF71E2A27C2 | 4C:8B05 0F4F7A00         | mov r8,qword ptr ds:[7FF71EA476D8]      |
00007FF71E2A27C9 | 48:8DBC24 30010000       | lea rdi,qword ptr ss:[rsp+130]          | [rsp+130]:sub_7FF71E191E83+5C
00007FF71E2A27D1 | 48:89F9                  | mov rcx,rdi                             |
00007FF71E2A27D4 | E8 DD590B00              | call <tauri-app.sub_7FF71E3581B6>       |
00007FF71E2A27D9 | 48:8D15 C8547000         | lea rdx,qword ptr ds:[7FF71E9A7CA8]     | 00007FF71E9A7CA8:&"/build\\source\\repos\\volt\\volt-monorepo\\apps\\desktop-interface\\.cargo-home\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tauri-2.9.2\\src\\async_runtime.rs"
00007FF71E2A27E0 | 48:8D8C24 D0080000       | lea rcx,qword ptr ss:[rsp+8D0]          |
00007FF71E2A27E8 | E8 5FFC0300              | call tauri-app.7FF71E2E244C             |
00007FF71E2A27ED | E9 831A0000              | jmp tauri-app.7FF71E2A4275              |
00007FF71E2A27F2 | 4C:8D05 2EB02B00         | lea r8,qword ptr ds:[7FF71E55D827]      | 00007FF71E55D827:"fail_token_refreshcomplete_session_token_responseread_fileread_file_base64write_filerename_filedelete_filecopy_filefile_existsopen_file_dialogsave_file_dialogopen_theme_file_dialogopen_theme_media_file_dialogsave_theme_file_dialogsave_file_to_scriptscreate_directorydirectory_existsdelete_directoryrename_directorylist_files_in_directorylist_directory_entriesget_scripts_directory_cmdget_autoexec_directory_cmdget_workspace_directory_cmdopen_folder_in_explorerensure_ignore_folderget_client_s
00007FF71E2A27F9 | 41:B9 12000000           | mov r9d,12                              |
00007FF71E2A27FF | 48:89F1                  | mov rcx,rsi                             |
00007FF71E2A2802 | 48:89FA                  | mov rdx,rdi                             |
00007FF71E2A2805 | E8 5B1EC8FF              | call <tauri-app.sub_7FF71DF24665>       |
00007FF71E2A280A | 84C0                     | test al,al                              |
00007FF71E2A280C | 0F84 16010000            | je tauri-app.7FF71E2A2928               |
00007FF71E2A2812 | 48:8D83 08020000         | lea rax,qword ptr ds:[rbx+208]          |
00007FF71E2A2819 | 4C:8B8B 88030000         | mov r9,qword ptr ds:[rbx+388]           |
00007FF71E2A2820 | 4C:8B93 90030000         | mov r10,qword ptr ds:[rbx+390]          |
00007FF71E2A2827 | 48:8B8B A8030000         | mov rcx,qword ptr ds:[rbx+3A8]          |
00007FF71E2A282E | 48:8D9424 206A0000       | lea rdx,qword ptr ss:[rsp+6A20]         |
00007FF71E2A2836 | 48:898A 18020000         | mov qword ptr ds:[rdx+218],rcx          |
00007FF71E2A283D | 0F1083 98030000          | movups xmm0,xmmword ptr ds:[rbx+398]    |
00007FF71E2A2844 | 0F1182 08020000          | movups xmmword ptr ds:[rdx+208],xmm0    |
00007FF71E2A284B | B9 08020000              | mov ecx,208                             |
00007FF71E2A2850 | 48:89D7                  | mov rdi,rdx                             |
00007FF71E2A2853 | 48:89DE                  | mov rsi,rbx                             |
00007FF71E2A2856 | F3:A4                    | rep movsb                               |
00007FF71E2A2858 | 4C:8D8424 580A0000       | lea r8,qword ptr ss:[rsp+A58]           |
00007FF71E2A2860 | B9 A0020000              | mov ecx,2A0                             |
00007FF71E2A2865 | 4C:89C7                  | mov rdi,r8                              |
00007FF71E2A2868 | 48:89D6                  | mov rsi,rdx                             |
00007FF71E2A286B | F3:A4                    | rep movsb                               |
00007FF71E2A286D | 45:31DB                  | xor r11d,r11d                           |
00007FF71E2A2870 | 45:8898 A0020000         | mov byte ptr ds:[r8+2A0],r11b           |
00007FF71E2A2877 | 48:8D9424 D0080000       | lea rdx,qword ptr ss:[rsp+8D0]          |
00007FF71E2A287F | B9 68010000              | mov ecx,168                             |
00007FF71E2A2884 | 48:89D7                  | mov rdi,rdx                             |
00007FF71E2A2887 | 48:89C6                  | mov rsi,rax                             |
00007FF71E2A288A | F3:A4                    | rep movsb                               |
00007FF71E2A288C | 4D:8948 F8               | mov qword ptr ds:[r8-8],r9              |
00007FF71E2A2890 | 0F1083 70030000          | movups xmm0,xmmword ptr ds:[rbx+370]    |
00007FF71E2A2897 | 41:0F1140 E0             | movups xmmword ptr ds:[r8-20],xmm0      |
00007FF71E2A289C | 48:8B83 80030000         | mov rax,qword ptr ds:[rbx+380]          |
00007FF71E2A28A3 | 49:8940 F0               | mov qword ptr ds:[r8-10],rax            |
00007FF71E2A28A7 | 4C:8992 D8060000         | mov qword ptr ds:[rdx+6D8],r10          |
00007FF71E2A28AE | 44:889A E0060000         | mov byte ptr ds:[rdx+6E0],r11b          |
00007FF71E2A28B5 | E8 C56DE8FF              | call tauri-app.7FF71E12967F             |
00007FF71E2A28BA | 833D DF4D7A00 02         | cmp dword ptr ds:[7FF71EA476A0],2       |
00007FF71E2A28C1 | 0F85 60010000            | jne tauri-app.7FF71E2A2A27              |
00007FF71E2A28C7 | 48:8B15 C24D7A00         | mov rdx,qword ptr ds:[7FF71EA47690]     |
00007FF71E2A28CE | 4C:8B05 C34D7A00         | mov r8,qword ptr ds:[7FF71EA47698]      |
00007FF71E2A28D5 | 48:8DBC24 30010000       | lea rdi,qword ptr ss:[rsp+130]          | [rsp+130]:sub_7FF71E191E83+5C
00007FF71E2A28DD | 48:89F9                  | mov rcx,rdi                             |
00007FF71E2A28E0 | E8 D1580B00              | call <tauri-app.sub_7FF71E3581B6>       |
00007FF71E2A28E5 | 48:8D15 A4537000         | lea rdx,qword ptr ds:[7FF71E9A7C90]     | 00007FF71E9A7C90:&"/build\\source\\repos\\volt\\volt-monorepo\\apps\\desktop-interface\\.cargo-home\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tauri-2.9.2\\src\\async_runtime.rs"
00007FF71E2A28EC | E9 5B010000              | jmp tauri-app.7FF71E2A2A4C              |
00007FF71E2A28F1 | 48:8B15 D84D7A00         | mov rdx,qword ptr ds:[7FF71EA476D0]     |
00007FF71E2A28F8 | 4C:8B05 D94D7A00         | mov r8,qword ptr ds:[7FF71EA476D8]      |
00007FF71E2A28FF | 48:8DBC24 30010000       | lea rdi,qword ptr ss:[rsp+130]          | [rsp+130]:sub_7FF71E191E83+5C
00007FF71E2A2907 | 48:89F9                  | mov rcx,rdi                             |
00007FF71E2A290A | E8 A7580B00              | call <tauri-app.sub_7FF71E3581B6>       |
00007FF71E2A290F | 48:8D15 92537000         | lea rdx,qword ptr ds:[7FF71E9A7CA8]     | 00007FF71E9A7CA8:&"/build\\source\\repos\\volt\\volt-monorepo\\apps\\desktop-interface\\.cargo-home\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tauri-2.9.2\\src\\async_runtime.rs"
00007FF71E2A2916 | 48:8D8C24 D0080000       | lea rcx,qword ptr ss:[rsp+8D0]          |
00007FF71E2A291E | E8 6DEC0300              | call <tauri-app.sub_7FF71E2E1590>       |
00007FF71E2A2923 | E9 4D190000              | jmp tauri-app.7FF71E2A4275              |
00007FF71E2A2928 | 4C:8D05 0AAF2B00         | lea r8,qword ptr ds:[7FF71E55D839]      | 00007FF71E55D839:"complete_session_token_responseread_fileread_file_base64write_filerename_filedelete_filecopy_filefile_existsopen_file_dialogsave_file_dialogopen_theme_file_dialogopen_theme_media_file_dialogsave_theme_file_dialogsave_file_to_scriptscreate_directorydirectory_existsdelete_directoryrename_directorylist_files_in_directorylist_directory_entriesget_scripts_directory_cmdget_autoexec_directory_cmdget_workspace_directory_cmdopen_folder_in_explorerensure_ignore_folderget_client_settingsupdate_clie
00007FF71E2A292F | 41:B9 1F000000           | mov r9d,1F                              |
00007FF71E2A2935 | 48:89F1                  | mov rcx,rsi                             |
00007FF71E2A2938 | 48:89FA                  | mov rdx,rdi                             |
00007FF71E2A293B | E8 251DC8FF              | call <tauri-app.sub_7FF71DF24665>       |
00007FF71E2A2940 | 84C0                     | test al,al                              |
00007FF71E2A2942 | 0F84 16010000            | je tauri-app.7FF71E2A2A5E               |
00007FF71E2A2948 | 48:8D83 08020000         | lea rax,qword ptr ds:[rbx+208]          |
00007FF71E2A294F | 4C:8B8B 88030000         | mov r9,qword ptr ds:[rbx+388]           |
00007FF71E2A2956 | 4C:8B93 90030000         | mov r10,qword ptr ds:[rbx+390]          |
00007FF71E2A295D | 48:8B8B A8030000         | mov rcx,qword ptr ds:[rbx+3A8]          |
00007FF71E2A2964 | 48:8D9424 206A0000       | lea rdx,qword ptr ss:[rsp+6A20]         |
00007FF71E2A296C | 48:898A 18020000         | mov qword ptr ds:[rdx+218],rcx          |
00007FF71E2A2973 | 0F1083 98030000          | movups xmm0,xmmword ptr ds:[rbx+398]    |
00007FF71E2A297A | 0F1182 08020000          | movups xmmword ptr ds:[rdx+208],xmm0    |
00007FF71E2A2981 | B9 08020000              | mov ecx,208                             |
00007FF71E2A2986 | 48:89D7                  | mov rdi,rdx                             |
00007FF71E2A2989 | 48:89DE                  | mov rsi,rbx                             |
00007FF71E2A298C | F3:A4                    | rep movsb                               |
00007FF71E2A298E | 4C:8D8424 580A0000       | lea r8,qword ptr ss:[rsp+A58]           |
00007FF71E2A2996 | B9 88050000              | mov ecx,588                             |
00007FF71E2A299B | 4C:89C7                  | mov rdi,r8                              |
00007FF71E2A299E | 48:89D6                  | mov rsi,rdx                             |
00007FF71E2A29A1 | F3:A4                    | rep movsb                               |
00007FF71E2A29A3 | 45:31DB                  | xor r11d,r11d                           |
00007FF71E2A29A6 | 45:8898 88050000         | mov byte ptr ds:[r8+588],r11b           |
00007FF71E2A29AD | 48:8D9424 D0080000       | lea rdx,qword ptr ss:[rsp+8D0]          |
00007FF71E2A29B5 | B9 68010000              | mov ecx,168                             |
00007FF71E2A29BA | 48:89D7                  | mov rdi,rdx                             |
00007FF71E2A29BD | 48:89C6                  | mov rsi,rax                             |
00007FF71E2A29C0 | F3:A4                    | rep movsb                               |
00007FF71E2A29C2 | 4D:8948 F8               | mov qword ptr ds:[r8-8],r9              |
00007FF71E2A29C6 | 0F1083 70030000          | movups xmm0,xmmword ptr ds:[rbx+370]    |
00007FF71E2A29CD | 41:0F1140 E0             | movups xmmword ptr ds:[r8-20],xmm0      |
00007FF71E2A29D2 | 48:8B83 80030000         | mov rax,qword ptr ds:[rbx+380]          |
00007FF71E2A29D9 | 49:8940 F0               | mov qword ptr ds:[r8-10],rax            |
00007FF71E2A29DD | 4C:8992 A80C0000         | mov qword ptr ds:[rdx+CA8],r10          |
00007FF71E2A29E4 | 44:889A B00C0000         | mov byte ptr ds:[rdx+CB0],r11b          |
00007FF71E2A29EB | E8 8F6CE8FF              | call tauri-app.7FF71E12967F             |
00007FF71E2A29F0 | 833D A94C7A00 02         | cmp dword ptr ds:[7FF71EA476A0],2       |
00007FF71E2A29F7 | 0F85 60010000            | jne tauri-app.7FF71E2A2B5D              |
00007FF71E2A29FD | 48:8B15 8C4C7A00         | mov rdx,qword ptr ds:[7FF71EA47690]     |
00007FF71E2A2A04 | 4C:8B05 8D4C7A00         | mov r8,qword ptr ds:[7FF71EA47698]      |
00007FF71E2A2A0B | 48:8DBC24 30010000       | lea rdi,qword ptr ss:[rsp+130]          | [rsp+130]:sub_7FF71E191E83+5C
00007FF71E2A2A13 | 48:89F9                  | mov rcx,rdi                             |
00007FF71E2A2A16 | E8 9B570B00              | call <tauri-app.sub_7FF71E3581B6>       |
00007FF71E2A2A1B | 48:8D15 6E527000         | lea rdx,qword ptr ds:[7FF71E9A7C90]     | 00007FF71E9A7C90:&"/build\\source\\repos\\volt\\volt-monorepo\\apps\\desktop-interface\\.cargo-home\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tauri-2.9.2\\src\\async_runtime.rs"
00007FF71E2A2A22 | E9 5B010000              | jmp tauri-app.7FF71E2A2B82              |
00007FF71E2A2A27 | 48:8B15 A24C7A00         | mov rdx,qword ptr ds:[7FF71EA476D0]     |
00007FF71E2A2A2E | 4C:8B05 A34C7A00         | mov r8,qword ptr ds:[7FF71EA476D8]      |
00007FF71E2A2A35 | 48:8DBC24 30010000       | lea rdi,qword ptr ss:[rsp+130]          | [rsp+130]:sub_7FF71E191E83+5C
00007FF71E2A2A3D | 48:89F9                  | mov rcx,rdi                             |
00007FF71E2A2A40 | E8 71570B00              | call <tauri-app.sub_7FF71E3581B6>       |
00007FF71E2A2A45 | 48:8D15 5C527000         | lea rdx,qword ptr ds:[7FF71E9A7CA8]     | 00007FF71E9A7CA8:&"/build\\source\\repos\\volt\\volt-monorepo\\apps\\desktop-interface\\.cargo-home\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tauri-2.9.2\\src\\async_runtime.rs"
00007FF71E2A2A4C | 48:8D8C24 D0080000       | lea rcx,qword ptr ss:[rsp+8D0]          |
00007FF71E2A2A54 | E8 E9DD0300              | call <tauri-app.sub_7FF71E2E0842>       |
00007FF71E2A2A59 | E9 17180000              | jmp tauri-app.7FF71E2A4275              |
00007FF71E2A2A5E | 4C:8D05 F3AD2B00         | lea r8,qword ptr ds:[7FF71E55D858]      | 00007FF71E55D858:"read_fileread_file_base64write_filerename_filedelete_filecopy_filefile_existsopen_file_dialogsave_file_dialogopen_theme_file_dialogopen_theme_media_file_dialogsave_theme_file_dialogsave_file_to_scriptscreate_directorydirectory_existsdelete_directoryrename_directorylist_files_in_directorylist_directory_entriesget_scripts_directory_cmdget_autoexec_directory_cmdget_workspace_directory_cmdopen_folder_in_explorerensure_ignore_folderget_client_settingsupdate_client_settingsget_roblox_path_cmdg
00007FF71E2A2A65 | 41:B9 09000000           | mov r9d,9                               | 09:'\t'
00007FF71E2A2A6B | 48:89F1                  | mov rcx,rsi                             |
00007FF71E2A2A6E | 48:89FA                  | mov rdx,rdi                             |
00007FF71E2A2A71 | E8 EF1BC8FF              | call <tauri-app.sub_7FF71DF24665>       |
00007FF71E2A2A76 | 84C0                     | test al,al                              |
00007FF71E2A2A78 | 0F84 16010000            | je tauri-app.7FF71E2A2B94               |
00007FF71E2A2A7E | 48:8D83 08020000         | lea rax,qword ptr ds:[rbx+208]          |
00007FF71E2A2A85 | 4C:8B8B 88030000         | mov r9,qword ptr ds:[rbx+388]           |
00007FF71E2A2A8C | 4C:8B93 90030000         | mov r10,qword ptr ds:[rbx+390]          |
00007FF71E2A2A93 | 48:8B8B A8030000         | mov rcx,qword ptr ds:[rbx+3A8]          |
00007FF71E2A2A9A | 48:8D9424 206A0000       | lea rdx,qword ptr ss:[rsp+6A20]         |
00007FF71E2A2AA2 | 48:898A 18020000         | mov qword ptr ds:[rdx+218],rcx          |
00007FF71E2A2AA9 | 0F1083 98030000          | movups xmm0,xmmword ptr ds:[rbx+398]    |
00007FF71E2A2AB0 | 0F1182 08020000          | movups xmmword ptr ds:[rdx+208],xmm0    |
00007FF71E2A2AB7 | B9 08020000              | mov ecx,208                             |
00007FF71E2A2ABC | 48:89D7                  | mov rdi,rdx                             |
00007FF71E2A2ABF | 48:89DE                  | mov rsi,rbx                             |
00007FF71E2A2AC2 | F3:A4                    | rep movsb                               |
00007FF71E2A2AC4 | 4C:8D8424 580A0000       | lea r8,qword ptr ss:[rsp+A58]           |
00007FF71E2A2ACC | B9 A8030000              | mov ecx,3A8                             |
00007FF71E2A2AD1 | 4C:89C7                  | mov rdi,r8                              |
00007FF71E2A2AD4 | 48:89D6                  | mov rsi,rdx                             |
00007FF71E2A2AD7 | F3:A4                    | rep movsb                               |
00007FF71E2A2AD9 | 45:31DB                  | xor r11d,r11d                           |
00007FF71E2A2ADC | 45:8898 A8030000         | mov byte ptr ds:[r8+3A8],r11b           |
00007FF71E2A2AE3 | 48:8D9424 D0080000       | lea rdx,qword ptr ss:[rsp+8D0]          |
00007FF71E2A2AEB | B9 68010000              | mov ecx,168                             |
00007FF71E2A2AF0 | 48:89D7                  | mov rdi,rdx                             |
00007FF71E2A2AF3 | 48:89C6                  | mov rsi,rax                             |
00007FF71E2A2AF6 | F3:A4                    | rep movsb                               |
00007FF71E2A2AF8 | 4D:8948 F8               | mov qword ptr ds:[r8-8],r9              |
00007FF71E2A2AFC | 0F1083 70030000          | movups xmm0,xmmword ptr ds:[rbx+370]    |
00007FF71E2A2B03 | 41:0F1140 E0             | movups xmmword ptr ds:[r8-20],xmm0      |
00007FF71E2A2B08 | 48:8B83 80030000         | mov rax,qword ptr ds:[rbx+380]          |
00007FF71E2A2B0F | 49:8940 F0               | mov qword ptr ds:[r8-10],rax            |
00007FF71E2A2B13 | 4C:8992 E8080000         | mov qword ptr ds:[rdx+8E8],r10          |
00007FF71E2A2B1A | 44:889A F0080000         | mov byte ptr ds:[rdx+8F0],r11b          |
00007FF71E2A2B21 | E8 596BE8FF              | call tauri-app.7FF71E12967F             |
00007FF71E2A2B26 | 833D 734B7A00 02         | cmp dword ptr ds:[7FF71EA476A0],2       |
00007FF71E2A2B2D | 0F85 60010000            | jne tauri-app.7FF71E2A2C93              |
00007FF71E2A2B33 | 48:8B15 564B7A00         | mov rdx,qword ptr ds:[7FF71EA47690]     |
00007FF71E2A2B3A | 4C:8B05 574B7A00         | mov r8,qword ptr ds:[7FF71EA47698]      |
00007FF71E2A2B41 | 48:8DBC24 30010000       | lea rdi,qword ptr ss:[rsp+130]          | [rsp+130]:sub_7FF71E191E83+5C
00007FF71E2A2B49 | 48:89F9                  | mov rcx,rdi                             |
00007FF71E2A2B4C | E8 65560B00              | call <tauri-app.sub_7FF71E3581B6>       |
00007FF71E2A2B51 | 48:8D15 38517000         | lea rdx,qword ptr ds:[7FF71E9A7C90]     | 00007FF71E9A7C90:&"/build\\source\\repos\\volt\\volt-monorepo\\apps\\desktop-interface\\.cargo-home\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tauri-2.9.2\\src\\async_runtime.rs"
00007FF71E2A2B58 | E9 5B010000              | jmp tauri-app.7FF71E2A2CB8              |
00007FF71E2A2B5D | 48:8B15 6C4B7A00         | mov rdx,qword ptr ds:[7FF71EA476D0]     |
00007FF71E2A2B64 | 4C:8B05 6D4B7A00         | mov r8,qword ptr ds:[7FF71EA476D8]      |
00007FF71E2A2B6B | 48:8DBC24 30010000       | lea rdi,qword ptr ss:[rsp+130]          | [rsp+130]:sub_7FF71E191E83+5C
00007FF71E2A2B73 | 48:89F9                  | mov rcx,rdi                             |
00007FF71E2A2B76 | E8 3B560B00              | call <tauri-app.sub_7FF71E3581B6>       |
00007FF71E2A2B7B | 48:8D15 26517000         | lea rdx,qword ptr ds:[7FF71E9A7CA8]     | 00007FF71E9A7CA8:&"/build\\source\\repos\\volt\\volt-monorepo\\apps\\desktop-interface\\.cargo-home\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tauri-2.9.2\\src\\async_runtime.rs"
00007FF71E2A2B82 | 48:8D8C24 D0080000       | lea rcx,qword ptr ss:[rsp+8D0]          |
00007FF71E2A2B8A | E8 29C30300              | call tauri-app.7FF71E2DEEB8             |
00007FF71E2A2B8F | E9 E1160000              | jmp tauri-app.7FF71E2A4275              |
00007FF71E2A2B94 | 4C:8D05 C6AC2B00         | lea r8,qword ptr ds:[7FF71E55D861]      | 00007FF71E55D861:"read_file_base64write_filerename_filedelete_filecopy_filefile_existsopen_file_dialogsave_file_dialogopen_theme_file_dialogopen_theme_media_file_dialogsave_theme_file_dialogsave_file_to_scriptscreate_directorydirectory_existsdelete_directoryrename_directorylist_files_in_directorylist_directory_entriesget_scripts_directory_cmdget_autoexec_directory_cmdget_workspace_directory_cmdopen_folder_in_explorerensure_ignore_folderget_client_settingsupdate_client_settingsget_roblox_path_cmdget_valida
00007FF71E2A2B9B | 41:B9 10000000           | mov r9d,10                              |
00007FF71E2A2BA1 | 48:89F1                  | mov rcx,rsi                             |
00007FF71E2A2BA4 | 48:89FA                  | mov rdx,rdi                             |
00007FF71E2A2BA7 | E8 B91AC8FF              | call <tauri-app.sub_7FF71DF24665>       |
00007FF71E2A2BAC | 84C0                     | test al,al                              |
00007FF71E2A2BAE | 0F84 16010000            | je tauri-app.7FF71E2A2CCA               |
00007FF71E2A2BB4 | 48:8D83 08020000         | lea rax,qword ptr ds:[rbx+208]          |
00007FF71E2A2BBB | 4C:8B8B 88030000         | mov r9,qword ptr ds:[rbx+388]           |
00007FF71E2A2BC2 | 4C:8B93 90030000         | mov r10,qword ptr ds:[rbx+390]          |
00007FF71E2A2BC9 | 48:8B8B A8030000         | mov rcx,qword ptr ds:[rbx+3A8]          |
00007FF71E2A2BD0 | 48:8D9424 206A0000       | lea rdx,qword ptr ss:[rsp+6A20]         |
00007FF71E2A2BD8 | 48:898A 18020000         | mov qword ptr ds:[rdx+218],rcx          |
00007FF71E2A2BDF | 0F1083 98030000          | movups xmm0,xmmword ptr ds:[rbx+398]    |
00007FF71E2A2BE6 | 0F1182 08020000          | movups xmmword ptr ds:[rdx+208],xmm0    |
00007FF71E2A2BED | B9 08020000              | mov ecx,208                             |
00007FF71E2A2BF2 | 48:89D7                  | mov rdi,rdx                             |
00007FF71E2A2BF5 | 48:89DE                  | mov rsi,rbx                             |
00007FF71E2A2BF8 | F3:A4                    | rep movsb                               |
00007FF71E2A2BFA | 4C:8D8424 580A0000       | lea r8,qword ptr ss:[rsp+A58]           |
00007FF71E2A2C02 | B9 A8030000              | mov ecx,3A8                             |
00007FF71E2A2C07 | 4C:89C7                  | mov rdi,r8                              |
00007FF71E2A2C0A | 48:89D6                  | mov rsi,rdx                             |
00007FF71E2A2C0D | F3:A4                    | rep movsb                               |
00007FF71E2A2C0F | 45:31DB                  | xor r11d,r11d                           |
00007FF71E2A2C12 | 45:8898 A8030000         | mov byte ptr ds:[r8+3A8],r11b           |
00007FF71E2A2C19 | 48:8D9424 D0080000       | lea rdx,qword ptr ss:[rsp+8D0]          |
00007FF71E2A2C21 | B9 68010000              | mov ecx,168                             |
00007FF71E2A2C26 | 48:89D7                  | mov rdi,rdx                             |
00007FF71E2A2C29 | 48:89C6                  | mov rsi,rax                             |
00007FF71E2A2C2C | F3:A4                    | rep movsb                               |
00007FF71E2A2C2E | 4D:8948 F8               | mov qword ptr ds:[r8-8],r9              |
00007FF71E2A2C32 | 0F1083 70030000          | movups xmm0,xmmword ptr ds:[rbx+370]    |
00007FF71E2A2C39 | 41:0F1140 E0             | movups xmmword ptr ds:[r8-20],xmm0      |
00007FF71E2A2C3E | 48:8B83 80030000         | mov rax,qword ptr ds:[rbx+380]          |
00007FF71E2A2C45 | 49:8940 F0               | mov qword ptr ds:[r8-10],rax            |
00007FF71E2A2C49 | 4C:8992 E8080000         | mov qword ptr ds:[rdx+8E8],r10          |
00007FF71E2A2C50 | 44:889A F0080000         | mov byte ptr ds:[rdx+8F0],r11b          |
00007FF71E2A2C57 | E8 236AE8FF              | call tauri-app.7FF71E12967F             |
00007FF71E2A2C5C | 833D 3D4A7A00 02         | cmp dword ptr ds:[7FF71EA476A0],2       |
00007FF71E2A2C63 | 0F85 60010000            | jne tauri-app.7FF71E2A2DC9              |
00007FF71E2A2C69 | 48:8B15 204A7A00         | mov rdx,qword ptr ds:[7FF71EA47690]     |
00007FF71E2A2C70 | 4C:8B05 214A7A00         | mov r8,qword ptr ds:[7FF71EA47698]      |
00007FF71E2A2C77 | 48:8DBC24 30010000       | lea rdi,qword ptr ss:[rsp+130]          | [rsp+130]:sub_7FF71E191E83+5C
00007FF71E2A2C7F | 48:89F9                  | mov rcx,rdi                             |
00007FF71E2A2C82 | E8 2F550B00              | call <tauri-app.sub_7FF71E3581B6>       |
00007FF71E2A2C87 | 48:8D15 02507000         | lea rdx,qword ptr ds:[7FF71E9A7C90]     | 00007FF71E9A7C90:&"/build\\source\\repos\\volt\\volt-monorepo\\apps\\desktop-interface\\.cargo-home\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tauri-2.9.2\\src\\async_runtime.rs"
00007FF71E2A2C8E | E9 5B010000              | jmp tauri-app.7FF71E2A2DEE              |
00007FF71E2A2C93 | 48:8B15 364A7A00         | mov rdx,qword ptr ds:[7FF71EA476D0]     |
00007FF71E2A2C9A | 4C:8B05 374A7A00         | mov r8,qword ptr ds:[7FF71EA476D8]      |
00007FF71E2A2CA1 | 48:8DBC24 30010000       | lea rdi,qword ptr ss:[rsp+130]          | [rsp+130]:sub_7FF71E191E83+5C
00007FF71E2A2CA9 | 48:89F9                  | mov rcx,rdi                             |
00007FF71E2A2CAC | E8 05550B00              | call <tauri-app.sub_7FF71E3581B6>       |
00007FF71E2A2CB1 | 48:8D15 F04F7000         | lea rdx,qword ptr ds:[7FF71E9A7CA8]     | 00007FF71E9A7CA8:&"/build\\source\\repos\\volt\\volt-monorepo\\apps\\desktop-interface\\.cargo-home\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tauri-2.9.2\\src\\async_runtime.rs"
00007FF71E2A2CB8 | 48:8D8C24 D0080000       | lea rcx,qword ptr ss:[rsp+8D0]          |
00007FF71E2A2CC0 | E8 88AC0300              | call tauri-app.7FF71E2DD94D             |
00007FF71E2A2CC5 | E9 AB150000              | jmp tauri-app.7FF71E2A4275              |
00007FF71E2A2CCA | 4C:8D05 A0AB2B00         | lea r8,qword ptr ds:[7FF71E55D871]      | 00007FF71E55D871:"write_filerename_filedelete_filecopy_filefile_existsopen_file_dialogsave_file_dialogopen_theme_file_dialogopen_theme_media_file_dialogsave_theme_file_dialogsave_file_to_scriptscreate_directorydirectory_existsdelete_directoryrename_directorylist_files_in_directorylist_directory_entriesget_scripts_directory_cmdget_autoexec_directory_cmdget_workspace_directory_cmdopen_folder_in_explorerensure_ignore_folderget_client_settingsupdate_client_settingsget_roblox_path_cmdget_validated_roblox_path_
00007FF71E2A2CD1 | 41:B9 0A000000           | mov r9d,A                               | 0A:'\n'
00007FF71E2A2CD7 | 48:89F1                  | mov rcx,rsi                             |
00007FF71E2A2CDA | 48:89FA                  | mov rdx,rdi                             |
00007FF71E2A2CDD | E8 8319C8FF              | call <tauri-app.sub_7FF71DF24665>       |
00007FF71E2A2CE2 | 84C0                     | test al,al                              |
00007FF71E2A2CE4 | 0F84 16010000            | je tauri-app.7FF71E2A2E00               |
00007FF71E2A2CEA | 48:8D83 08020000         | lea rax,qword ptr ds:[rbx+208]          |
00007FF71E2A2CF1 | 4C:8B8B 88030000         | mov r9,qword ptr ds:[rbx+388]           |
00007FF71E2A2CF8 | 4C:8B93 90030000         | mov r10,qword ptr ds:[rbx+390]          |
00007FF71E2A2CFF | 48:8B8B A8030000         | mov rcx,qword ptr ds:[rbx+3A8]          |
00007FF71E2A2D06 | 48:8D9424 206A0000       | lea rdx,qword ptr ss:[rsp+6A20]         |
00007FF71E2A2D0E | 48:898A 18020000         | mov qword ptr ds:[rdx+218],rcx          |
00007FF71E2A2D15 | 0F1083 98030000          | movups xmm0,xmmword ptr ds:[rbx+398]    |
00007FF71E2A2D1C | 0F1182 08020000          | movups xmmword ptr ds:[rdx+208],xmm0    |
00007FF71E2A2D23 | B9 08020000              | mov ecx,208                             |
00007FF71E2A2D28 | 48:89D7                  | mov rdi,rdx                             |
00007FF71E2A2D2B | 48:89DE                  | mov rsi,rbx                             |
00007FF71E2A2D2E | F3:A4                    | rep movsb                               |
00007FF71E2A2D30 | 4C:8D8424 580A0000       | lea r8,qword ptr ss:[rsp+A58]           |
00007FF71E2A2D38 | B9 40050000              | mov ecx,540                             |
00007FF71E2A2D3D | 4C:89C7                  | mov rdi,r8                              |
00007FF71E2A2D40 | 48:89D6                  | mov rsi,rdx                             |
00007FF71E2A2D43 | F3:A4                    | rep movsb                               |
00007FF71E2A2D45 | 45:31DB                  | xor r11d,r11d                           |
00007FF71E2A2D48 | 45:8898 40050000         | mov byte ptr ds:[r8+540],r11b           |
00007FF71E2A2D4F | 48:8D9424 D0080000       | lea rdx,qword ptr ss:[rsp+8D0]          |
00007FF71E2A2D57 | B9 68010000              | mov ecx,168                             |
00007FF71E2A2D5C | 48:89D7                  | mov rdi,rdx                             |
00007FF71E2A2D5F | 48:89C6                  | mov rsi,rax                             |
00007FF71E2A2D62 | F3:A4                    | rep movsb                               |
00007FF71E2A2D64 | 4D:8948 F8               | mov qword ptr ds:[r8-8],r9              |
00007FF71E2A2D68 | 0F1083 70030000          | movups xmm0,xmmword ptr ds:[rbx+370]    |
00007FF71E2A2D6F | 41:0F1140 E0             | movups xmmword ptr ds:[r8-20],xmm0      |
00007FF71E2A2D74 | 48:8B83 80030000         | mov rax,qword ptr ds:[rbx+380]          |
00007FF71E2A2D7B | 49:8940 F0               | mov qword ptr ds:[r8-10],rax            |
00007FF71E2A2D7F | 4C:8992 180C0000         | mov qword ptr ds:[rdx+C18],r10          |
00007FF71E2A2D86 | 44:889A 200C0000         | mov byte ptr ds:[rdx+C20],r11b          |
00007FF71E2A2D8D | E8 ED68E8FF              | call tauri-app.7FF71E12967F             |
00007FF71E2A2D92 | 833D 07497A00 02         | cmp dword ptr ds:[7FF71EA476A0],2       |
00007FF71E2A2D99 | 0F85 60010000            | jne tauri-app.7FF71E2A2EFF              |
00007FF71E2A2D9F | 48:8B15 EA487A00         | mov rdx,qword ptr ds:[7FF71EA47690]     |
00007FF71E2A2DA6 | 4C:8B05 EB487A00         | mov r8,qword ptr ds:[7FF71EA47698]      |
00007FF71E2A2DAD | 48:8DBC24 30010000       | lea rdi,qword ptr ss:[rsp+130]          | [rsp+130]:sub_7FF71E191E83+5C
00007FF71E2A2DB5 | 48:89F9                  | mov rcx,rdi                             |
00007FF71E2A2DB8 | E8 F9530B00              | call <tauri-app.sub_7FF71E3581B6>       |
00007FF71E2A2DBD | 48:8D15 CC4E7000         | lea rdx,qword ptr ds:[7FF71E9A7C90]     | 00007FF71E9A7C90:&"/build\\source\\repos\\volt\\volt-monorepo\\apps\\desktop-interface\\.cargo-home\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tauri-2.9.2\\src\\async_runtime.rs"
00007FF71E2A2DC4 | E9 5B010000              | jmp tauri-app.7FF71E2A2F24              |
00007FF71E2A2DC9 | 48:8B15 00497A00         | mov rdx,qword ptr ds:[7FF71EA476D0]     |
00007FF71E2A2DD0 | 4C:8B05 01497A00         | mov r8,qword ptr ds:[7FF71EA476D8]      |
00007FF71E2A2DD7 | 48:8DBC24 30010000       | lea rdi,qword ptr ss:[rsp+130]          | [rsp+130]:sub_7FF71E191E83+5C
00007FF71E2A2DDF | 48:89F9                  | mov rcx,rdi                             |
00007FF71E2A2DE2 | E8 CF530B00              | call <tauri-app.sub_7FF71E3581B6>       |
00007FF71E2A2DE7 | 48:8D15 BA4E7000         | lea rdx,qword ptr ds:[7FF71E9A7CA8]     | 00007FF71E9A7CA8:&"/build\\source\\repos\\volt\\volt-monorepo\\apps\\desktop-interface\\.cargo-home\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tauri-2.9.2\\src\\async_runtime.rs"
00007FF71E2A2DEE | 48:8D8C24 D0080000       | lea rcx,qword ptr ss:[rsp+8D0]          |
00007FF71E2A2DF6 | E8 4E8B0300              | call <tauri-app.sub_7FF71E2DB949>       |
00007FF71E2A2DFB | E9 75140000              | jmp tauri-app.7FF71E2A4275              |
00007FF71E2A2E00 | 4C:8D05 74AA2B00         | lea r8,qword ptr ds:[7FF71E55D87B]      | 00007FF71E55D87B:"rename_filedelete_filecopy_filefile_existsopen_file_dialogsave_file_dialogopen_theme_file_dialogopen_theme_media_file_dialogsave_theme_file_dialogsave_file_to_scriptscreate_directorydirectory_existsdelete_directoryrename_directorylist_files_in_directorylist_directory_entriesget_scripts_directory_cmdget_autoexec_directory_cmdget_workspace_directory_cmdopen_folder_in_explorerensure_ignore_folderget_client_settingsupdate_client_settingsget_roblox_path_cmdget_validated_roblox_path_cmdvalidat
00007FF71E2A2E07 | 41:B9 0B000000           | mov r9d,B                               | 0B:'\v'
00007FF71E2A2E0D | 48:89F1                  | mov rcx,rsi                             |
00007FF71E2A2E10 | 48:89FA                  | mov rdx,rdi                             |
00007FF71E2A2E13 | E8 4D18C8FF              | call <tauri-app.sub_7FF71DF24665>       |
00007FF71E2A2E18 | 84C0                     | test al,al                              |
00007FF71E2A2E1A | 0F84 16010000            | je tauri-app.7FF71E2A2F36               |
00007FF71E2A2E20 | 48:8D83 08020000         | lea rax,qword ptr ds:[rbx+208]          |
00007FF71E2A2E27 | 4C:8B8B 88030000         | mov r9,qword ptr ds:[rbx+388]           |
00007FF71E2A2E2E | 4C:8B93 90030000         | mov r10,qword ptr ds:[rbx+390]          |
00007FF71E2A2E35 | 48:8B8B A8030000         | mov rcx,qword ptr ds:[rbx+3A8]          |
00007FF71E2A2E3C | 48:8D9424 206A0000       | lea rdx,qword ptr ss:[rsp+6A20]         |
00007FF71E2A2E44 | 48:898A 18020000         | mov qword ptr ds:[rdx+218],rcx          |
00007FF71E2A2E4B | 0F1083 98030000          | movups xmm0,xmmword ptr ds:[rbx+398]    |
00007FF71E2A2E52 | 0F1182 08020000          | movups xmmword ptr ds:[rdx+208],xmm0    |
00007FF71E2A2E59 | B9 08020000              | mov ecx,208                             |
00007FF71E2A2E5E | 48:89D7                  | mov rdi,rdx                             |
00007FF71E2A2E61 | 48:89DE                  | mov rsi,rbx                             |
00007FF71E2A2E64 | F3:A4                    | rep movsb                               |
00007FF71E2A2E66 | 4C:8D8424 580A0000       | lea r8,qword ptr ss:[rsp+A58]           |
00007FF71E2A2E6E | B9 88050000              | mov ecx,588                             |
00007FF71E2A2E73 | 4C:89C7                  | mov rdi,r8                              |
00007FF71E2A2E76 | 48:89D6                  | mov rsi,rdx                             |
00007FF71E2A2E79 | F3:A4                    | rep movsb                               |
00007FF71E2A2E7B | 45:31DB                  | xor r11d,r11d                           |
00007FF71E2A2E7E | 45:8898 88050000         | mov byte ptr ds:[r8+588],r11b           |
00007FF71E2A2E85 | 48:8D9424 D0080000       | lea rdx,qword ptr ss:[rsp+8D0]          |
00007FF71E2A2E8D | B9 68010000              | mov ecx,168                             |
00007FF71E2A2E92 | 48:89D7                  | mov rdi,rdx                             |
00007FF71E2A2E95 | 48:89C6                  | mov rsi,rax                             |
00007FF71E2A2E98 | F3:A4                    | rep movsb                               |
00007FF71E2A2E9A | 4D:8948 F8               | mov qword ptr ds:[r8-8],r9              |
00007FF71E2A2E9E | 0F1083 70030000          | movups xmm0,xmmword ptr ds:[rbx+370]    |
00007FF71E2A2EA5 | 41:0F1140 E0             | movups xmmword ptr ds:[r8-20],xmm0      |
00007FF71E2A2EAA | 48:8B83 80030000         | mov rax,qword ptr ds:[rbx+380]          |
00007FF71E2A2EB1 | 49:8940 F0               | mov qword ptr ds:[r8-10],rax            |
00007FF71E2A2EB5 | 4C:8992 A80C0000         | mov qword ptr ds:[rdx+CA8],r10          |
00007FF71E2A2EBC | 44:889A B00C0000         | mov byte ptr ds:[rdx+CB0],r11b          |
00007FF71E2A2EC3 | E8 B767E8FF              | call tauri-app.7FF71E12967F             |
00007FF71E2A2EC8 | 833D D1477A00 02         | cmp dword ptr ds:[7FF71EA476A0],2       |
00007FF71E2A2ECF | 0F85 60010000            | jne tauri-app.7FF71E2A3035              |
00007FF71E2A2ED5 | 48:8B15 B4477A00         | mov rdx,qword ptr ds:[7FF71EA47690]     |
00007FF71E2A2EDC | 4C:8B05 B5477A00         | mov r8,qword ptr ds:[7FF71EA47698]      |
00007FF71E2A2EE3 | 48:8DBC24 30010000       | lea rdi,qword ptr ss:[rsp+130]          | [rsp+130]:sub_7FF71E191E83+5C
00007FF71E2A2EEB | 48:89F9                  | mov rcx,rdi                             |
00007FF71E2A2EEE | E8 C3520B00              | call <tauri-app.sub_7FF71E3581B6>       |
00007FF71E2A2EF3 | 48:8D15 964D7000         | lea rdx,qword ptr ds:[7FF71E9A7C90]     | 00007FF71E9A7C90:&"/build\\source\\repos\\volt\\volt-monorepo\\apps\\desktop-interface\\.cargo-home\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tauri-2.9.2\\src\\async_runtime.rs"
00007FF71E2A2EFA | E9 5B010000              | jmp tauri-app.7FF71E2A305A              |
00007FF71E2A2EFF | 48:8B15 CA477A00         | mov rdx,qword ptr ds:[7FF71EA476D0]     |
00007FF71E2A2F06 | 4C:8B05 CB477A00         | mov r8,qword ptr ds:[7FF71EA476D8]      |
00007FF71E2A2F0D | 48:8DBC24 30010000       | lea rdi,qword ptr ss:[rsp+130]          | [rsp+130]:sub_7FF71E191E83+5C
00007FF71E2A2F15 | 48:89F9                  | mov rcx,rdi                             |
00007FF71E2A2F18 | E8 99520B00              | call <tauri-app.sub_7FF71E3581B6>       |
00007FF71E2A2F1D | 48:8D15 844D7000         | lea rdx,qword ptr ds:[7FF71E9A7CA8]     | 00007FF71E9A7CA8:&"/build\\source\\repos\\volt\\volt-monorepo\\apps\\desktop-interface\\.cargo-home\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tauri-2.9.2\\src\\async_runtime.rs"
00007FF71E2A2F24 | 48:8D8C24 D0080000       | lea rcx,qword ptr ss:[rsp+8D0]          |
00007FF71E2A2F2C | E8 81780300              | call <tauri-app.sub_7FF71E2DA7B2>       |
00007FF71E2A2F31 | E9 3F130000              | jmp tauri-app.7FF71E2A4275              |
00007FF71E2A2F36 | 4C:8D05 49A92B00         | lea r8,qword ptr ds:[7FF71E55D886]      | 00007FF71E55D886:"delete_filecopy_filefile_existsopen_file_dialogsave_file_dialogopen_theme_file_dialogopen_theme_media_file_dialogsave_theme_file_dialogsave_file_to_scriptscreate_directorydirectory_existsdelete_directoryrename_directorylist_files_in_directorylist_directory_entriesget_scripts_directory_cmdget_autoexec_directory_cmdget_workspace_directory_cmdopen_folder_in_explorerensure_ignore_folderget_client_settingsupdate_client_settingsget_roblox_path_cmdget_validated_roblox_path_cmdvalidate_roblox_pa
00007FF71E2A2F3D | 41:B9 0B000000           | mov r9d,B                               | 0B:'\v'
00007FF71E2A2F43 | 48:89F1                  | mov rcx,rsi                             |
00007FF71E2A2F46 | 48:89FA                  | mov rdx,rdi                             |
00007FF71E2A2F49 | E8 1717C8FF              | call <tauri-app.sub_7FF71DF24665>       |
00007FF71E2A2F4E | 84C0                     | test al,al                              |
00007FF71E2A2F50 | 0F84 16010000            | je tauri-app.7FF71E2A306C               |
00007FF71E2A2F56 | 48:8D83 08020000         | lea rax,qword ptr ds:[rbx+208]          |
00007FF71E2A2F5D | 4C:8B8B 88030000         | mov r9,qword ptr ds:[rbx+388]           |
00007FF71E2A2F64 | 4C:8B93 90030000         | mov r10,qword ptr ds:[rbx+390]          |
00007FF71E2A2F6B | 48:8B8B A8030000         | mov rcx,qword ptr ds:[rbx+3A8]          |
00007FF71E2A2F72 | 48:8D9424 206A0000       | lea rdx,qword ptr ss:[rsp+6A20]         |
00007FF71E2A2F7A | 48:898A 18020000         | mov qword ptr ds:[rdx+218],rcx          |
00007FF71E2A2F81 | 0F1083 98030000          | movups xmm0,xmmword ptr ds:[rbx+398]    |
00007FF71E2A2F88 | 0F1182 08020000          | movups xmmword ptr ds:[rdx+208],xmm0    |
00007FF71E2A2F8F | B9 08020000              | mov ecx,208                             |
00007FF71E2A2F94 | 48:89D7                  | mov rdi,rdx                             |
00007FF71E2A2F97 | 48:89DE                  | mov rsi,rbx                             |
00007FF71E2A2F9A | F3:A4                    | rep movsb                               |
00007FF71E2A2F9C | 4C:8D8424 580A0000       | lea r8,qword ptr ss:[rsp+A58]           |
00007FF71E2A2FA4 | B9 08040000              | mov ecx,408                             |
00007FF71E2A2FA9 | 4C:89C7                  | mov rdi,r8                              |
00007FF71E2A2FAC | 48:89D6                  | mov rsi,rdx                             |
00007FF71E2A2FAF | F3:A4                    | rep movsb                               |
00007FF71E2A2FB1 | 45:31DB                  | xor r11d,r11d                           |
00007FF71E2A2FB4 | 45:8898 08040000         | mov byte ptr ds:[r8+408],r11b           |
00007FF71E2A2FBB | 48:8D9424 D0080000       | lea rdx,qword ptr ss:[rsp+8D0]          |
00007FF71E2A2FC3 | B9 68010000              | mov ecx,168                             |
00007FF71E2A2FC8 | 48:89D7                  | mov rdi,rdx                             |
00007FF71E2A2FCB | 48:89C6                  | mov rsi,rax                             |
00007FF71E2A2FCE | F3:A4                    | rep movsb                               |
00007FF71E2A2FD0 | 4D:8948 F8               | mov qword ptr ds:[r8-8],r9              |
00007FF71E2A2FD4 | 0F1083 70030000          | movups xmm0,xmmword ptr ds:[rbx+370]    |
00007FF71E2A2FDB | 41:0F1140 E0             | movups xmmword ptr ds:[r8-20],xmm0      |
00007FF71E2A2FE0 | 48:8B83 80030000         | mov rax,qword ptr ds:[rbx+380]          |
00007FF71E2A2FE7 | 49:8940 F0               | mov qword ptr ds:[r8-10],rax            |
00007FF71E2A2FEB | 4C:8992 A8090000         | mov qword ptr ds:[rdx+9A8],r10          |
00007FF71E2A2FF2 | 44:889A B0090000         | mov byte ptr ds:[rdx+9B0],r11b          |
00007FF71E2A2FF9 | E8 8166E8FF              | call tauri-app.7FF71E12967F             |
00007FF71E2A2FFE | 833D 9B467A00 02         | cmp dword ptr ds:[7FF71EA476A0],2       |
00007FF71E2A3005 | 0F85 60010000            | jne tauri-app.7FF71E2A316B              |
00007FF71E2A300B | 48:8B15 7E467A00         | mov rdx,qword ptr ds:[7FF71EA47690]     |
00007FF71E2A3012 | 4C:8B05 7F467A00         | mov r8,qword ptr ds:[7FF71EA47698]      |
00007FF71E2A3019 | 48:8DBC24 30010000       | lea rdi,qword ptr ss:[rsp+130]          | [rsp+130]:sub_7FF71E191E83+5C
00007FF71E2A3021 | 48:89F9                  | mov rcx,rdi                             |
00007FF71E2A3024 | E8 8D510B00              | call <tauri-app.sub_7FF71E3581B6>       |
00007FF71E2A3029 | 48:8D15 604C7000         | lea rdx,qword ptr ds:[7FF71E9A7C90]     | 00007FF71E9A7C90:&"/build\\source\\repos\\volt\\volt-monorepo\\apps\\desktop-interface\\.cargo-home\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tauri-2.9.2\\src\\async_runtime.rs"
00007FF71E2A3030 | E9 5B010000              | jmp tauri-app.7FF71E2A3190              |
00007FF71E2A3035 | 48:8B15 94467A00         | mov rdx,qword ptr ds:[7FF71EA476D0]     |
00007FF71E2A303C | 4C:8B05 95467A00         | mov r8,qword ptr ds:[7FF71EA476D8]      |
00007FF71E2A3043 | 48:8DBC24 30010000       | lea rdi,qword ptr ss:[rsp+130]          | [rsp+130]:sub_7FF71E191E83+5C
00007FF71E2A304B | 48:89F9                  | mov rcx,rdi                             |
00007FF71E2A304E | E8 63510B00              | call <tauri-app.sub_7FF71E3581B6>       |
00007FF71E2A3053 | 48:8D15 4E4C7000         | lea rdx,qword ptr ds:[7FF71E9A7CA8]     | 00007FF71E9A7CA8:&"/build\\source\\repos\\volt\\volt-monorepo\\apps\\desktop-interface\\.cargo-home\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tauri-2.9.2\\src\\async_runtime.rs"
00007FF71E2A305A | 48:8D8C24 D0080000       | lea rcx,qword ptr ss:[rsp+8D0]          |
00007FF71E2A3062 | E8 6C670300              | call <tauri-app.sub_7FF71E2D97D3>       |
00007FF71E2A3067 | E9 09120000              | jmp tauri-app.7FF71E2A4275              |
00007FF71E2A306C | 4C:8D05 1EA82B00         | lea r8,qword ptr ds:[7FF71E55D891]      | 00007FF71E55D891:"copy_filefile_existsopen_file_dialogsave_file_dialogopen_theme_file_dialogopen_theme_media_file_dialogsave_theme_file_dialogsave_file_to_scriptscreate_directorydirectory_existsdelete_directoryrename_directorylist_files_in_directorylist_directory_entriesget_scripts_directory_cmdget_autoexec_directory_cmdget_workspace_directory_cmdopen_folder_in_explorerensure_ignore_folderget_client_settingsupdate_client_settingsget_roblox_path_cmdget_validated_roblox_path_cmdvalidate_roblox_path_cmdroblo
00007FF71E2A3073 | 41:B9 09000000           | mov r9d,9                               | 09:'\t'
00007FF71E2A3079 | 48:89F1                  | mov rcx,rsi                             |
00007FF71E2A307C | 48:89FA                  | mov rdx,rdi                             |
00007FF71E2A307F | E8 E115C8FF              | call <tauri-app.sub_7FF71DF24665>       |
00007FF71E2A3084 | 84C0                     | test al,al                              |
00007FF71E2A3086 | 0F84 16010000            | je tauri-app.7FF71E2A31A2               |
00007FF71E2A308C | 48:8D83 08020000         | lea rax,qword ptr ds:[rbx+208]          |
00007FF71E2A3093 | 4C:8B8B 88030000         | mov r9,qword ptr ds:[rbx+388]           |
00007FF71E2A309A | 4C:8B93 90030000         | mov r10,qword ptr ds:[rbx+390]          |
00007FF71E2A30A1 | 48:8B8B A8030000         | mov rcx,qword ptr ds:[rbx+3A8]          |
00007FF71E2A30A8 | 48:8D9424 206A0000       | lea rdx,qword ptr ss:[rsp+6A20]         |
00007FF71E2A30B0 | 48:898A 18020000         | mov qword ptr ds:[rdx+218],rcx          |
00007FF71E2A30B7 | 0F1083 98030000          | movups xmm0,xmmword ptr ds:[rbx+398]    |
00007FF71E2A30BE | 0F1182 08020000          | movups xmmword ptr ds:[rdx+208],xmm0    |
00007FF71E2A30C5 | B9 08020000              | mov ecx,208                             |
00007FF71E2A30CA | 48:89D7                  | mov rdi,rdx                             |
00007FF71E2A30CD | 48:89DE                  | mov rsi,rbx                             |
00007FF71E2A30D0 | F3:A4                    | rep movsb                               |
00007FF71E2A30D2 | 4C:8D8424 580A0000       | lea r8,qword ptr ss:[rsp+A58]           |
00007FF71E2A30DA | B9 88050000              | mov ecx,588                             |
00007FF71E2A30DF | 4C:89C7                  | mov rdi,r8                              |
00007FF71E2A30E2 | 48:89D6                  | mov rsi,rdx                             |
00007FF71E2A30E5 | F3:A4                    | rep movsb                               |
00007FF71E2A30E7 | 45:31DB                  | xor r11d,r11d                           |
00007FF71E2A30EA | 45:8898 88050000         | mov byte ptr ds:[r8+588],r11b           |
00007FF71E2A30F1 | 48:8D9424 D0080000       | lea rdx,qword ptr ss:[rsp+8D0]          |
00007FF71E2A30F9 | B9 68010000              | mov ecx,168                             |
00007FF71E2A30FE | 48:89D7                  | mov rdi,rdx                             |
00007FF71E2A3101 | 48:89C6                  | mov rsi,rax                             |
00007FF71E2A3104 | F3:A4                    | rep movsb                               |
00007FF71E2A3106 | 4D:8948 F8               | mov qword ptr ds:[r8-8],r9              |
00007FF71E2A310A | 0F1083 70030000          | movups xmm0,xmmword ptr ds:[rbx+370]    |
00007FF71E2A3111 | 41:0F1140 E0             | movups xmmword ptr ds:[r8-20],xmm0      |
00007FF71E2A3116 | 48:8B83 80030000         | mov rax,qword ptr ds:[rbx+380]          |
00007FF71E2A311D | 49:8940 F0               | mov qword ptr ds:[r8-10],rax            |
00007FF71E2A3121 | 4C:8992 A80C0000         | mov qword ptr ds:[rdx+CA8],r10          |
00007FF71E2A3128 | 44:889A B00C0000         | mov byte ptr ds:[rdx+CB0],r11b          |
00007FF71E2A312F | E8 4B65E8FF              | call tauri-app.7FF71E12967F             |
00007FF71E2A3134 | 833D 65457A00 02         | cmp dword ptr ds:[7FF71EA476A0],2       |
00007FF71E2A313B | 0F85 60010000            | jne tauri-app.7FF71E2A32A1              |
00007FF71E2A3141 | 48:8B15 48457A00         | mov rdx,qword ptr ds:[7FF71EA47690]     |
00007FF71E2A3148 | 4C:8B05 49457A00         | mov r8,qword ptr ds:[7FF71EA47698]      |
00007FF71E2A314F | 48:8DBC24 30010000       | lea rdi,qword ptr ss:[rsp+130]          | [rsp+130]:sub_7FF71E191E83+5C
00007FF71E2A3157 | 48:89F9                  | mov rcx,rdi                             |
00007FF71E2A315A | E8 57500B00              | call <tauri-app.sub_7FF71E3581B6>       |
00007FF71E2A315F | 48:8D15 2A4B7000         | lea rdx,qword ptr ds:[7FF71E9A7C90]     | 00007FF71E9A7C90:&"/build\\source\\repos\\volt\\volt-monorepo\\apps\\desktop-interface\\.cargo-home\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tauri-2.9.2\\src\\async_runtime.rs"
00007FF71E2A3166 | E9 5B010000              | jmp tauri-app.7FF71E2A32C6              |
00007FF71E2A316B | 48:8B15 5E457A00         | mov rdx,qword ptr ds:[7FF71EA476D0]     |
00007FF71E2A3172 | 4C:8B05 5F457A00         | mov r8,qword ptr ds:[7FF71EA476D8]      |
00007FF71E2A3179 | 48:8DBC24 30010000       | lea rdi,qword ptr ss:[rsp+130]          | [rsp+130]:sub_7FF71E191E83+5C
00007FF71E2A3181 | 48:89F9                  | mov rcx,rdi                             |
00007FF71E2A3184 | E8 2D500B00              | call <tauri-app.sub_7FF71E3581B6>       |
00007FF71E2A3189 | 48:8D15 184B7000         | lea rdx,qword ptr ds:[7FF71E9A7CA8]     | 00007FF71E9A7CA8:&"/build\\source\\repos\\volt\\volt-monorepo\\apps\\desktop-interface\\.cargo-home\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tauri-2.9.2\\src\\async_runtime.rs"
00007FF71E2A3190 | 48:8D8C24 D0080000       | lea rcx,qword ptr ss:[rsp+8D0]          |
00007FF71E2A3198 | E8 54590300              | call <tauri-app.sub_7FF71E2D8AF1>       |
00007FF71E2A319D | E9 D3100000              | jmp tauri-app.7FF71E2A4275              |
00007FF71E2A31A2 | 4C:8D05 F1A62B00         | lea r8,qword ptr ds:[7FF71E55D89A]      | 00007FF71E55D89A:"file_existsopen_file_dialogsave_file_dialogopen_theme_file_dialogopen_theme_media_file_dialogsave_theme_file_dialogsave_file_to_scriptscreate_directorydirectory_existsdelete_directoryrename_directorylist_files_in_directorylist_directory_entriesget_scripts_directory_cmdget_autoexec_directory_cmdget_workspace_directory_cmdopen_folder_in_explorerensure_ignore_folderget_client_settingsupdate_client_settingsget_roblox_path_cmdget_validated_roblox_path_cmdvalidate_roblox_path_cmdroblox_exists_
00007FF71E2A31A9 | 41:B9 0B000000           | mov r9d,B                               | 0B:'\v'
00007FF71E2A31AF | 48:89F1                  | mov rcx,rsi                             |
00007FF71E2A31B2 | 48:89FA                  | mov rdx,rdi                             |
00007FF71E2A31B5 | E8 AB14C8FF              | call <tauri-app.sub_7FF71DF24665>       |
00007FF71E2A31BA | 84C0                     | test al,al                              |
00007FF71E2A31BC | 0F84 16010000            | je tauri-app.7FF71E2A32D8               |
00007FF71E2A31C2 | 48:8D83 08020000         | lea rax,qword ptr ds:[rbx+208]          |
00007FF71E2A31C9 | 4C:8B8B 88030000         | mov r9,qword ptr ds:[rbx+388]           |
00007FF71E2A31D0 | 4C:8B93 90030000         | mov r10,qword ptr ds:[rbx+390]          |
00007FF71E2A31D7 | 48:8B8B A8030000         | mov rcx,qword ptr ds:[rbx+3A8]          |
00007FF71E2A31DE | 48:8D9424 206A0000       | lea rdx,qword ptr ss:[rsp+6A20]         |
00007FF71E2A31E6 | 48:898A 18020000         | mov qword ptr ds:[rdx+218],rcx          |
00007FF71E2A31ED | 0F1083 98030000          | movups xmm0,xmmword ptr ds:[rbx+398]    |
00007FF71E2A31F4 | 0F1182 08020000          | movups xmmword ptr ds:[rdx+208],xmm0    |
00007FF71E2A31FB | B9 08020000              | mov ecx,208                             |
00007FF71E2A3200 | 48:89D7                  | mov rdi,rdx                             |
00007FF71E2A3203 | 48:89DE                  | mov rsi,rbx                             |
00007FF71E2A3206 | F3:A4                    | rep movsb                               |
00007FF71E2A3208 | 4C:8D8424 580A0000       | lea r8,qword ptr ss:[rsp+A58]           |
00007FF71E2A3210 | B9 88020000              | mov ecx,288                             |
00007FF71E2A3215 | 4C:89C7                  | mov rdi,r8                              |
00007FF71E2A3218 | 48:89D6                  | mov rsi,rdx                             |
00007FF71E2A321B | F3:A4                    | rep movsb                               |
00007FF71E2A321D | 45:31DB                  | xor r11d,r11d                           |
00007FF71E2A3220 | 45:8898 88020000         | mov byte ptr ds:[r8+288],r11b           |
00007FF71E2A3227 | 48:8D9424 D0080000       | lea rdx,qword ptr ss:[rsp+8D0]          |
00007FF71E2A322F | B9 68010000              | mov ecx,168                             |
00007FF71E2A3234 | 48:89D7                  | mov rdi,rdx                             |
00007FF71E2A3237 | 48:89C6                  | mov rsi,rax                             |
00007FF71E2A323A | F3:A4                    | rep movsb                               |
00007FF71E2A323C | 4D:8948 F8               | mov qword ptr ds:[r8-8],r9              |
00007FF71E2A3240 | 0F1083 70030000          | movups xmm0,xmmword ptr ds:[rbx+370]    |
00007FF71E2A3247 | 41:0F1140 E0             | movups xmmword ptr ds:[r8-20],xmm0      |
00007FF71E2A324C | 48:8B83 80030000         | mov rax,qword ptr ds:[rbx+380]          |
00007FF71E2A3253 | 49:8940 F0               | mov qword ptr ds:[r8-10],rax            |
00007FF71E2A3257 | 4C:8992 A8060000         | mov qword ptr ds:[rdx+6A8],r10          |
00007FF71E2A325E | 44:889A B0060000         | mov byte ptr ds:[rdx+6B0],r11b          |
00007FF71E2A3265 | E8 1564E8FF              | call tauri-app.7FF71E12967F             |
00007FF71E2A326A | 833D 2F447A00 02         | cmp dword ptr ds:[7FF71EA476A0],2       |
00007FF71E2A3271 | 0F85 60010000            | jne tauri-app.7FF71E2A33D7              |
00007FF71E2A3277 | 48:8B15 12447A00         | mov rdx,qword ptr ds:[7FF71EA47690]     |
00007FF71E2A327E | 4C:8B05 13447A00         | mov r8,qword ptr ds:[7FF71EA47698]      |
00007FF71E2A3285 | 48:8DBC24 30010000       | lea rdi,qword ptr ss:[rsp+130]          | [rsp+130]:sub_7FF71E191E83+5C
00007FF71E2A328D | 48:89F9                  | mov rcx,rdi                             |
00007FF71E2A3290 | E8 214F0B00              | call <tauri-app.sub_7FF71E3581B6>       |
00007FF71E2A3295 | 48:8D15 F4497000         | lea rdx,qword ptr ds:[7FF71E9A7C90]     | 00007FF71E9A7C90:&"/build\\source\\repos\\volt\\volt-monorepo\\apps\\desktop-interface\\.cargo-home\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tauri-2.9.2\\src\\async_runtime.rs"
00007FF71E2A329C | E9 5B010000              | jmp tauri-app.7FF71E2A33FC              |
00007FF71E2A32A1 | 48:8B15 28447A00         | mov rdx,qword ptr ds:[7FF71EA476D0]     |
00007FF71E2A32A8 | 4C:8B05 29447A00         | mov r8,qword ptr ds:[7FF71EA476D8]      |
00007FF71E2A32AF | 48:8DBC24 30010000       | lea rdi,qword ptr ss:[rsp+130]          | [rsp+130]:sub_7FF71E191E83+5C
00007FF71E2A32B7 | 48:89F9                  | mov rcx,rdi                             |
00007FF71E2A32BA | E8 F74E0B00              | call <tauri-app.sub_7FF71E3581B6>       |
00007FF71E2A32BF | 48:8D15 E2497000         | lea rdx,qword ptr ds:[7FF71E9A7CA8]     | 00007FF71E9A7CA8:&"/build\\source\\repos\\volt\\volt-monorepo\\apps\\desktop-interface\\.cargo-home\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tauri-2.9.2\\src\\async_runtime.rs"
00007FF71E2A32C6 | 48:8D8C24 D0080000       | lea rcx,qword ptr ss:[rsp+8D0]          |
00007FF71E2A32CE | E8 A03D0300              | call <tauri-app.sub_7FF71E2D7073>       |
00007FF71E2A32D3 | E9 9D0F0000              | jmp tauri-app.7FF71E2A4275              |
00007FF71E2A32D8 | 4C:8D05 C6A52B00         | lea r8,qword ptr ds:[7FF71E55D8A5]      | 00007FF71E55D8A5:"open_file_dialogsave_file_dialogopen_theme_file_dialogopen_theme_media_file_dialogsave_theme_file_dialogsave_file_to_scriptscreate_directorydirectory_existsdelete_directoryrename_directorylist_files_in_directorylist_directory_entriesget_scripts_directory_cmdget_autoexec_directory_cmdget_workspace_directory_cmdopen_folder_in_explorerensure_ignore_folderget_client_settingsupdate_client_settingsget_roblox_path_cmdget_validated_roblox_path_cmdvalidate_roblox_path_cmdroblox_exists_cmdget_robl
00007FF71E2A32DF | 41:B9 10000000           | mov r9d,10                              |
00007FF71E2A32E5 | 48:89F1                  | mov rcx,rsi                             |
00007FF71E2A32E8 | 48:89FA                  | mov rdx,rdi                             |
00007FF71E2A32EB | E8 7513C8FF              | call <tauri-app.sub_7FF71DF24665>       |
00007FF71E2A32F0 | 84C0                     | test al,al                              |
00007FF71E2A32F2 | 0F84 16010000            | je tauri-app.7FF71E2A340E               |
00007FF71E2A32F8 | 48:8D83 08020000         | lea rax,qword ptr ds:[rbx+208]          |
00007FF71E2A32FF | 4C:8B8B 88030000         | mov r9,qword ptr ds:[rbx+388]           |
00007FF71E2A3306 | 4C:8B93 90030000         | mov r10,qword ptr ds:[rbx+390]          |
00007FF71E2A330D | 48:8B8B A8030000         | mov rcx,qword ptr ds:[rbx+3A8]          |
00007FF71E2A3314 | 48:8D9424 206A0000       | lea rdx,qword ptr ss:[rsp+6A20]         |
00007FF71E2A331C | 48:898A 18020000         | mov qword ptr ds:[rdx+218],rcx          |
00007FF71E2A3323 | 0F1083 98030000          | movups xmm0,xmmword ptr ds:[rbx+398]    |
00007FF71E2A332A | 0F1182 08020000          | movups xmmword ptr ds:[rdx+208],xmm0    |
00007FF71E2A3331 | B9 08020000              | mov ecx,208                             |
00007FF71E2A3336 | 48:89D7                  | mov rdi,rdx                             |
00007FF71E2A3339 | 48:89DE                  | mov rsi,rbx                             |
00007FF71E2A333C | F3:A4                    | rep movsb                               |
00007FF71E2A333E | 4C:8D8424 580A0000       | lea r8,qword ptr ss:[rsp+A58]           |
00007FF71E2A3346 | B9 08040000              | mov ecx,408                             |
00007FF71E2A334B | 4C:89C7                  | mov rdi,r8                              |
00007FF71E2A334E | 48:89D6                  | mov rsi,rdx                             |
00007FF71E2A3351 | F3:A4                    | rep movsb                               |
00007FF71E2A3353 | 45:31DB                  | xor r11d,r11d                           |
00007FF71E2A3356 | 45:8898 08040000         | mov byte ptr ds:[r8+408],r11b           |
00007FF71E2A335D | 48:8D9424 D0080000       | lea rdx,qword ptr ss:[rsp+8D0]          |
00007FF71E2A3365 | B9 68010000              | mov ecx,168                             |
00007FF71E2A336A | 48:89D7                  | mov rdi,rdx                             |
00007FF71E2A336D | 48:89C6                  | mov rsi,rax                             |
00007FF71E2A3370 | F3:A4                    | rep movsb                               |
00007FF71E2A3372 | 4D:8948 F8               | mov qword ptr ds:[r8-8],r9              |
00007FF71E2A3376 | 0F1083 70030000          | movups xmm0,xmmword ptr ds:[rbx+370]    |
00007FF71E2A337D | 41:0F1140 E0             | movups xmmword ptr ds:[r8-20],xmm0      |
00007FF71E2A3382 | 48:8B83 80030000         | mov rax,qword ptr ds:[rbx+380]          |
00007FF71E2A3389 | 49:8940 F0               | mov qword ptr ds:[r8-10],rax            |
00007FF71E2A338D | 4C:8992 A8090000         | mov qword ptr ds:[rdx+9A8],r10          |
00007FF71E2A3394 | 44:889A B0090000         | mov byte ptr ds:[rdx+9B0],r11b          |
00007FF71E2A339B | E8 DF62E8FF              | call tauri-app.7FF71E12967F             |
00007FF71E2A33A0 | 833D F9427A00 02         | cmp dword ptr ds:[7FF71EA476A0],2       |
00007FF71E2A33A7 | 0F85 60010000            | jne tauri-app.7FF71E2A350D              |
00007FF71E2A33AD | 48:8B15 DC427A00         | mov rdx,qword ptr ds:[7FF71EA47690]     |
00007FF71E2A33B4 | 4C:8B05 DD427A00         | mov r8,qword ptr ds:[7FF71EA47698]      |
00007FF71E2A33BB | 48:8DBC24 30010000       | lea rdi,qword ptr ss:[rsp+130]          | [rsp+130]:sub_7FF71E191E83+5C
00007FF71E2A33C3 | 48:89F9                  | mov rcx,rdi                             |
00007FF71E2A33C6 | E8 EB4D0B00              | call <tauri-app.sub_7FF71E3581B6>       |
00007FF71E2A33CB | 48:8D15 BE487000         | lea rdx,qword ptr ds:[7FF71E9A7C90]     | 00007FF71E9A7C90:&"/build\\source\\repos\\volt\\volt-monorepo\\apps\\desktop-interface\\.cargo-home\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tauri-2.9.2\\src\\async_runtime.rs"
00007FF71E2A33D2 | E9 5B010000              | jmp tauri-app.7FF71E2A3532              |
00007FF71E2A33D7 | 48:8B15 F2427A00         | mov rdx,qword ptr ds:[7FF71EA476D0]     |
00007FF71E2A33DE | 4C:8B05 F3427A00         | mov r8,qword ptr ds:[7FF71EA476D8]      |
00007FF71E2A33E5 | 48:8DBC24 30010000       | lea rdi,qword ptr ss:[rsp+130]          | [rsp+130]:sub_7FF71E191E83+5C
00007FF71E2A33ED | 48:89F9                  | mov rcx,rdi                             |
00007FF71E2A33F0 | E8 C14D0B00              | call <tauri-app.sub_7FF71E3581B6>       |
00007FF71E2A33F5 | 48:8D15 AC487000         | lea rdx,qword ptr ds:[7FF71E9A7CA8]     | 00007FF71E9A7CA8:&"/build\\source\\repos\\volt\\volt-monorepo\\apps\\desktop-interface\\.cargo-home\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tauri-2.9.2\\src\\async_runtime.rs"
00007FF71E2A33FC | 48:8D8C24 D0080000       | lea rcx,qword ptr ss:[rsp+8D0]          |
00007FF71E2A3404 | E8 55310300              | call <tauri-app.sub_7FF71E2D655E>       |
00007FF71E2A3409 | E9 670E0000              | jmp tauri-app.7FF71E2A4275              |
00007FF71E2A340E | 4C:8D05 A0A42B00         | lea r8,qword ptr ds:[7FF71E55D8B5]      | 00007FF71E55D8B5:"save_file_dialogopen_theme_file_dialogopen_theme_media_file_dialogsave_theme_file_dialogsave_file_to_scriptscreate_directorydirectory_existsdelete_directoryrename_directorylist_files_in_directorylist_directory_entriesget_scripts_directory_cmdget_autoexec_directory_cmdget_workspace_directory_cmdopen_folder_in_explorerensure_ignore_folderget_client_settingsupdate_client_settingsget_roblox_path_cmdget_validated_roblox_path_cmdvalidate_roblox_path_cmdroblox_exists_cmdget_roblox_exe_path_cmdg
00007FF71E2A3415 | 41:B9 10000000           | mov r9d,10                              |
00007FF71E2A341B | 48:89F1                  | mov rcx,rsi                             |
00007FF71E2A341E | 48:89FA                  | mov rdx,rdi                             |
00007FF71E2A3421 | E8 3F12C8FF              | call <tauri-app.sub_7FF71DF24665>       |
00007FF71E2A3426 | 84C0                     | test al,al                              |
00007FF71E2A3428 | 0F84 16010000            | je tauri-app.7FF71E2A3544               |
00007FF71E2A342E | 48:8D83 08020000         | lea rax,qword ptr ds:[rbx+208]          |
00007FF71E2A3435 | 4C:8B8B 88030000         | mov r9,qword ptr ds:[rbx+388]           |
00007FF71E2A343C | 4C:8B93 90030000         | mov r10,qword ptr ds:[rbx+390]          |
00007FF71E2A3443 | 48:8B8B A8030000         | mov rcx,qword ptr ds:[rbx+3A8]          |
00007FF71E2A344A | 48:8D9424 206A0000       | lea rdx,qword ptr ss:[rsp+6A20]         |
00007FF71E2A3452 | 48:898A 18020000         | mov qword ptr ds:[rdx+218],rcx          |
00007FF71E2A3459 | 0F1083 98030000          | movups xmm0,xmmword ptr ds:[rbx+398]    |
00007FF71E2A3460 | 0F1182 08020000          | movups xmmword ptr ds:[rdx+208],xmm0    |
00007FF71E2A3467 | B9 08020000              | mov ecx,208                             |
00007FF71E2A346C | 48:89D7                  | mov rdi,rdx                             |
00007FF71E2A346F | 48:89DE                  | mov rsi,rbx                             |
00007FF71E2A3472 | F3:A4                    | rep movsb                               |
00007FF71E2A3474 | 4C:8D8424 580A0000       | lea r8,qword ptr ss:[rsp+A58]           |
00007FF71E2A347C | B9 08040000              | mov ecx,408                             |
00007FF71E2A3481 | 4C:89C7                  | mov rdi,r8                              |
00007FF71E2A3484 | 48:89D6                  | mov rsi,rdx                             |
00007FF71E2A3487 | F3:A4                    | rep movsb                               |
00007FF71E2A3489 | 45:31DB                  | xor r11d,r11d                           |
00007FF71E2A348C | 45:8898 08040000         | mov byte ptr ds:[r8+408],r11b           |
00007FF71E2A3493 | 48:8D9424 D0080000       | lea rdx,qword ptr ss:[rsp+8D0]          |
00007FF71E2A349B | B9 68010000              | mov ecx,168                             |
00007FF71E2A34A0 | 48:89D7                  | mov rdi,rdx                             |
00007FF71E2A34A3 | 48:89C6                  | mov rsi,rax                             |
00007FF71E2A34A6 | F3:A4                    | rep movsb                               |
00007FF71E2A34A8 | 4D:8948 F8               | mov qword ptr ds:[r8-8],r9              |
00007FF71E2A34AC | 0F1083 70030000          | movups xmm0,xmmword ptr ds:[rbx+370]    |
00007FF71E2A34B3 | 41:0F1140 E0             | movups xmmword ptr ds:[r8-20],xmm0      |
00007FF71E2A34B8 | 48:8B83 80030000         | mov rax,qword ptr ds:[rbx+380]          |
00007FF71E2A34BF | 49:8940 F0               | mov qword ptr ds:[r8-10],rax            |
00007FF71E2A34C3 | 4C:8992 A8090000         | mov qword ptr ds:[rdx+9A8],r10          |
00007FF71E2A34CA | 44:889A B0090000         | mov byte ptr ds:[rdx+9B0],r11b          |
00007FF71E2A34D1 | E8 A961E8FF              | call tauri-app.7FF71E12967F             |
00007FF71E2A34D6 | 833D C3417A00 02         | cmp dword ptr ds:[7FF71EA476A0],2       |
00007FF71E2A34DD | 0F85 60010000            | jne tauri-app.7FF71E2A3643              |
00007FF71E2A34E3 | 48:8B15 A6417A00         | mov rdx,qword ptr ds:[7FF71EA47690]     |
00007FF71E2A34EA | 4C:8B05 A7417A00         | mov r8,qword ptr ds:[7FF71EA47698]      |
00007FF71E2A34F1 | 48:8DBC24 30010000       | lea rdi,qword ptr ss:[rsp+130]          | [rsp+130]:sub_7FF71E191E83+5C
00007FF71E2A34F9 | 48:89F9                  | mov rcx,rdi                             |
00007FF71E2A34FC | E8 B54C0B00              | call <tauri-app.sub_7FF71E3581B6>       |
00007FF71E2A3501 | 48:8D15 88477000         | lea rdx,qword ptr ds:[7FF71E9A7C90]     | 00007FF71E9A7C90:&"/build\\source\\repos\\volt\\volt-monorepo\\apps\\desktop-interface\\.cargo-home\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tauri-2.9.2\\src\\async_runtime.rs"
00007FF71E2A3508 | E9 5B010000              | jmp tauri-app.7FF71E2A3668              |
00007FF71E2A350D | 48:8B15 BC417A00         | mov rdx,qword ptr ds:[7FF71EA476D0]     |
00007FF71E2A3514 | 4C:8B05 BD417A00         | mov r8,qword ptr ds:[7FF71EA476D8]      |
00007FF71E2A351B | 48:8DBC24 30010000       | lea rdi,qword ptr ss:[rsp+130]          | [rsp+130]:sub_7FF71E191E83+5C
00007FF71E2A3523 | 48:89F9                  | mov rcx,rdi                             |
00007FF71E2A3526 | E8 8B4C0B00              | call <tauri-app.sub_7FF71E3581B6>       |
00007FF71E2A352B | 48:8D15 76477000         | lea rdx,qword ptr ds:[7FF71E9A7CA8]     | 00007FF71E9A7CA8:&"/build\\source\\repos\\volt\\volt-monorepo\\apps\\desktop-interface\\.cargo-home\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tauri-2.9.2\\src\\async_runtime.rs"
00007FF71E2A3532 | 48:8D8C24 D0080000       | lea rcx,qword ptr ss:[rsp+8D0]          |
00007FF71E2A353A | E8 DB1F0300              | call <tauri-app.sub_7FF71E2D551A>       |
00007FF71E2A353F | E9 310D0000              | jmp tauri-app.7FF71E2A4275              |
00007FF71E2A3544 | 4C:8D05 7AA32B00         | lea r8,qword ptr ds:[7FF71E55D8C5]      | 00007FF71E55D8C5:"open_theme_file_dialogopen_theme_media_file_dialogsave_theme_file_dialogsave_file_to_scriptscreate_directorydirectory_existsdelete_directoryrename_directorylist_files_in_directorylist_directory_entriesget_scripts_directory_cmdget_autoexec_directory_cmdget_workspace_directory_cmdopen_folder_in_explorerensure_ignore_folderget_client_settingsupdate_client_settingsget_roblox_path_cmdget_validated_roblox_path_cmdvalidate_roblox_path_cmdroblox_exists_cmdget_roblox_exe_path_cmdget_roblox_versio
00007FF71E2A354B | 41:B9 16000000           | mov r9d,16                              |
00007FF71E2A3551 | 48:89F1                  | mov rcx,rsi                             |
00007FF71E2A3554 | 48:89FA                  | mov rdx,rdi                             |
00007FF71E2A3557 | E8 0911C8FF              | call <tauri-app.sub_7FF71DF24665>       |
00007FF71E2A355C | 84C0                     | test al,al                              |
00007FF71E2A355E | 0F84 16010000            | je tauri-app.7FF71E2A367A               |
00007FF71E2A3564 | 48:8D83 08020000         | lea rax,qword ptr ds:[rbx+208]          |
00007FF71E2A356B | 4C:8B8B 88030000         | mov r9,qword ptr ds:[rbx+388]           |
00007FF71E2A3572 | 4C:8B93 90030000         | mov r10,qword ptr ds:[rbx+390]          |
00007FF71E2A3579 | 48:8B8B A8030000         | mov rcx,qword ptr ds:[rbx+3A8]          |
00007FF71E2A3580 | 48:8D9424 206A0000       | lea rdx,qword ptr ss:[rsp+6A20]         |
00007FF71E2A3588 | 48:898A 18020000         | mov qword ptr ds:[rdx+218],rcx          |
00007FF71E2A358F | 0F1083 98030000          | movups xmm0,xmmword ptr ds:[rbx+398]    |
00007FF71E2A3596 | 0F1182 08020000          | movups xmmword ptr ds:[rdx+208],xmm0    |
00007FF71E2A359D | B9 08020000              | mov ecx,208                             |
00007FF71E2A35A2 | 48:89D7                  | mov rdi,rdx                             |
00007FF71E2A35A5 | 48:89DE                  | mov rsi,rbx                             |
00007FF71E2A35A8 | F3:A4                    | rep movsb                               |
00007FF71E2A35AA | 4C:8D8424 580A0000       | lea r8,qword ptr ss:[rsp+A58]           |
00007FF71E2A35B2 | B9 08040000              | mov ecx,408                             |
00007FF71E2A35B7 | 4C:89C7                  | mov rdi,r8                              |
00007FF71E2A35BA | 48:89D6                  | mov rsi,rdx                             |
00007FF71E2A35BD | F3:A4                    | rep movsb                               |
00007FF71E2A35BF | 45:31DB                  | xor r11d,r11d                           |
00007FF71E2A35C2 | 45:8898 08040000         | mov byte ptr ds:[r8+408],r11b           |
00007FF71E2A35C9 | 48:8D9424 D0080000       | lea rdx,qword ptr ss:[rsp+8D0]          |
00007FF71E2A35D1 | B9 68010000              | mov ecx,168                             |
00007FF71E2A35D6 | 48:89D7                  | mov rdi,rdx                             |
00007FF71E2A35D9 | 48:89C6                  | mov rsi,rax                             |
00007FF71E2A35DC | F3:A4                    | rep movsb                               |
00007FF71E2A35DE | 4D:8948 F8               | mov qword ptr ds:[r8-8],r9              |
00007FF71E2A35E2 | 0F1083 70030000          | movups xmm0,xmmword ptr ds:[rbx+370]    |
00007FF71E2A35E9 | 41:0F1140 E0             | movups xmmword ptr ds:[r8-20],xmm0      |
00007FF71E2A35EE | 48:8B83 80030000         | mov rax,qword ptr ds:[rbx+380]          |
00007FF71E2A35F5 | 49:8940 F0               | mov qword ptr ds:[r8-10],rax            |
00007FF71E2A35F9 | 4C:8992 A8090000         | mov qword ptr ds:[rdx+9A8],r10          |
00007FF71E2A3600 | 44:889A B0090000         | mov byte ptr ds:[rdx+9B0],r11b          |
00007FF71E2A3607 | E8 7360E8FF              | call tauri-app.7FF71E12967F             |
00007FF71E2A360C | 833D 8D407A00 02         | cmp dword ptr ds:[7FF71EA476A0],2       |
00007FF71E2A3613 | 0F85 60010000            | jne tauri-app.7FF71E2A3779              |
00007FF71E2A3619 | 48:8B15 70407A00         | mov rdx,qword ptr ds:[7FF71EA47690]     |
00007FF71E2A3620 | 4C:8B05 71407A00         | mov r8,qword ptr ds:[7FF71EA47698]      |
00007FF71E2A3627 | 48:8DBC24 30010000       | lea rdi,qword ptr ss:[rsp+130]          | [rsp+130]:sub_7FF71E191E83+5C
00007FF71E2A362F | 48:89F9                  | mov rcx,rdi                             |
00007FF71E2A3632 | E8 7F4B0B00              | call <tauri-app.sub_7FF71E3581B6>       |
00007FF71E2A3637 | 48:8D15 52467000         | lea rdx,qword ptr ds:[7FF71E9A7C90]     | 00007FF71E9A7C90:&"/build\\source\\repos\\volt\\volt-monorepo\\apps\\desktop-interface\\.cargo-home\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tauri-2.9.2\\src\\async_runtime.rs"
00007FF71E2A363E | E9 5B010000              | jmp tauri-app.7FF71E2A379E              |
00007FF71E2A3643 | 48:8B15 86407A00         | mov rdx,qword ptr ds:[7FF71EA476D0]     |
00007FF71E2A364A | 4C:8B05 87407A00         | mov r8,qword ptr ds:[7FF71EA476D8]      |
00007FF71E2A3651 | 48:8DBC24 30010000       | lea rdi,qword ptr ss:[rsp+130]          | [rsp+130]:sub_7FF71E191E83+5C
00007FF71E2A3659 | 48:89F9                  | mov rcx,rdi                             |
00007FF71E2A365C | E8 554B0B00              | call <tauri-app.sub_7FF71E3581B6>       |
00007FF71E2A3661 | 48:8D15 40467000         | lea rdx,qword ptr ds:[7FF71E9A7CA8]     | 00007FF71E9A7CA8:&"/build\\source\\repos\\volt\\volt-monorepo\\apps\\desktop-interface\\.cargo-home\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tauri-2.9.2\\src\\async_runtime.rs"
00007FF71E2A3668 | 48:8D8C24 D0080000       | lea rcx,qword ptr ss:[rsp+8D0]          |
00007FF71E2A3670 | E8 720E0300              | call <tauri-app.sub_7FF71E2D44E7>       |
00007FF71E2A3675 | E9 FB0B0000              | jmp tauri-app.7FF71E2A4275              |
00007FF71E2A367A | 4C:8D05 5AA22B00         | lea r8,qword ptr ds:[7FF71E55D8DB]      | 00007FF71E55D8DB:"open_theme_media_file_dialogsave_theme_file_dialogsave_file_to_scriptscreate_directorydirectory_existsdelete_directoryrename_directorylist_files_in_directorylist_directory_entriesget_scripts_directory_cmdget_autoexec_directory_cmdget_workspace_directory_cmdopen_folder_in_explorerensure_ignore_folderget_client_settingsupdate_client_settingsget_roblox_path_cmdget_validated_roblox_path_cmdvalidate_roblox_path_cmdroblox_exists_cmdget_roblox_exe_path_cmdget_roblox_version_cmdpick_roblox_direc
00007FF71E2A3681 | 41:B9 1C000000           | mov r9d,1C                              |
00007FF71E2A3687 | 48:89F1                  | mov rcx,rsi                             |
00007FF71E2A368A | 48:89FA                  | mov rdx,rdi                             |
00007FF71E2A368D | E8 D30FC8FF              | call <tauri-app.sub_7FF71DF24665>       |
00007FF71E2A3692 | 84C0                     | test al,al                              |
00007FF71E2A3694 | 0F84 16010000            | je tauri-app.7FF71E2A37B0               |
00007FF71E2A369A | 48:8D83 08020000         | lea rax,qword ptr ds:[rbx+208]          |
00007FF71E2A36A1 | 4C:8B8B 88030000         | mov r9,qword ptr ds:[rbx+388]           |
00007FF71E2A36A8 | 4C:8B93 90030000         | mov r10,qword ptr ds:[rbx+390]          |
00007FF71E2A36AF | 48:8B8B A8030000         | mov rcx,qword ptr ds:[rbx+3A8]          |
00007FF71E2A36B6 | 48:8D9424 206A0000       | lea rdx,qword ptr ss:[rsp+6A20]         |
00007FF71E2A36BE | 48:898A 18020000         | mov qword ptr ds:[rdx+218],rcx          |
00007FF71E2A36C5 | 0F1083 98030000          | movups xmm0,xmmword ptr ds:[rbx+398]    |
00007FF71E2A36CC | 0F1182 08020000          | movups xmmword ptr ds:[rdx+208],xmm0    |
00007FF71E2A36D3 | B9 08020000              | mov ecx,208                             |
00007FF71E2A36D8 | 48:89D7                  | mov rdi,rdx                             |
00007FF71E2A36DB | 48:89DE                  | mov rsi,rbx                             |
00007FF71E2A36DE | F3:A4                    | rep movsb                               |
00007FF71E2A36E0 | 4C:8D8424 580A0000       | lea r8,qword ptr ss:[rsp+A58]           |
00007FF71E2A36E8 | B9 08040000              | mov ecx,408                             |
00007FF71E2A36ED | 4C:89C7                  | mov rdi,r8                              |
00007FF71E2A36F0 | 48:89D6                  | mov rsi,rdx                             |
00007FF71E2A36F3 | F3:A4                    | rep movsb                               |
00007FF71E2A36F5 | 45:31DB                  | xor r11d,r11d                           |
00007FF71E2A36F8 | 45:8898 08040000         | mov byte ptr ds:[r8+408],r11b           |
00007FF71E2A36FF | 48:8D9424 D0080000       | lea rdx,qword ptr ss:[rsp+8D0]          |
00007FF71E2A3707 | B9 68010000              | mov ecx,168                             |
00007FF71E2A370C | 48:89D7                  | mov rdi,rdx                             |
00007FF71E2A370F | 48:89C6                  | mov rsi,rax                             |
00007FF71E2A3712 | F3:A4                    | rep movsb                               |
00007FF71E2A3714 | 4D:8948 F8               | mov qword ptr ds:[r8-8],r9              |
00007FF71E2A3718 | 0F1083 70030000          | movups xmm0,xmmword ptr ds:[rbx+370]    |
00007FF71E2A371F | 41:0F1140 E0             | movups xmmword ptr ds:[r8-20],xmm0      |
00007FF71E2A3724 | 48:8B83 80030000         | mov rax,qword ptr ds:[rbx+380]          |
00007FF71E2A372B | 49:8940 F0               | mov qword ptr ds:[r8-10],rax            |
00007FF71E2A372F | 4C:8992 A8090000         | mov qword ptr ds:[rdx+9A8],r10          |
00007FF71E2A3736 | 44:889A B0090000         | mov byte ptr ds:[rdx+9B0],r11b          |
00007FF71E2A373D | E8 3D5FE8FF              | call tauri-app.7FF71E12967F             |
00007FF71E2A3742 | 833D 573F7A00 02         | cmp dword ptr ds:[7FF71EA476A0],2       |
00007FF71E2A3749 | 0F85 60010000            | jne tauri-app.7FF71E2A38AF              |
00007FF71E2A374F | 48:8B15 3A3F7A00         | mov rdx,qword ptr ds:[7FF71EA47690]     |
00007FF71E2A3756 | 4C:8B05 3B3F7A00         | mov r8,qword ptr ds:[7FF71EA47698]      |
00007FF71E2A375D | 48:8DBC24 30010000       | lea rdi,qword ptr ss:[rsp+130]          | [rsp+130]:sub_7FF71E191E83+5C
00007FF71E2A3765 | 48:89F9                  | mov rcx,rdi                             |
00007FF71E2A3768 | E8 494A0B00              | call <tauri-app.sub_7FF71E3581B6>       |
00007FF71E2A376D | 48:8D15 1C457000         | lea rdx,qword ptr ds:[7FF71E9A7C90]     | 00007FF71E9A7C90:&"/build\\source\\repos\\volt\\volt-monorepo\\apps\\desktop-interface\\.cargo-home\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tauri-2.9.2\\src\\async_runtime.rs"
00007FF71E2A3774 | E9 5B010000              | jmp tauri-app.7FF71E2A38D4              |
00007FF71E2A3779 | 48:8B15 503F7A00         | mov rdx,qword ptr ds:[7FF71EA476D0]     |
00007FF71E2A3780 | 4C:8B05 513F7A00         | mov r8,qword ptr ds:[7FF71EA476D8]      |
00007FF71E2A3787 | 48:8DBC24 30010000       | lea rdi,qword ptr ss:[rsp+130]          | [rsp+130]:sub_7FF71E191E83+5C
00007FF71E2A378F | 48:89F9                  | mov rcx,rdi                             |
00007FF71E2A3792 | E8 1F4A0B00              | call <tauri-app.sub_7FF71E3581B6>       |
00007FF71E2A3797 | 48:8D15 0A457000         | lea rdx,qword ptr ds:[7FF71E9A7CA8]     | 00007FF71E9A7CA8:&"/build\\source\\repos\\volt\\volt-monorepo\\apps\\desktop-interface\\.cargo-home\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tauri-2.9.2\\src\\async_runtime.rs"
00007FF71E2A379E | 48:8D8C24 D0080000       | lea rcx,qword ptr ss:[rsp+8D0]          |
00007FF71E2A37A6 | E8 D1FD0200              | call <tauri-app.sub_7FF71E2D357C>       |
00007FF71E2A37AB | E9 C50A0000              | jmp tauri-app.7FF71E2A4275              |
00007FF71E2A37B0 | 4C:8D05 40A12B00         | lea r8,qword ptr ds:[7FF71E55D8F7]      | 00007FF71E55D8F7:"save_theme_file_dialogsave_file_to_scriptscreate_directorydirectory_existsdelete_directoryrename_directorylist_files_in_directorylist_directory_entriesget_scripts_directory_cmdget_autoexec_directory_cmdget_workspace_directory_cmdopen_folder_in_explorerensure_ignore_folderget_client_settingsupdate_client_settingsget_roblox_path_cmdget_validated_roblox_path_cmdvalidate_roblox_path_cmdroblox_exists_cmdget_roblox_exe_path_cmdget_roblox_version_cmdpick_roblox_directoryvalidate_and_update_robl
00007FF71E2A37B7 | 41:B9 16000000           | mov r9d,16                              |
00007FF71E2A37BD | 48:89F1                  | mov rcx,rsi                             |
00007FF71E2A37C0 | 48:89FA                  | mov rdx,rdi                             |
00007FF71E2A37C3 | E8 9D0EC8FF              | call <tauri-app.sub_7FF71DF24665>       |
00007FF71E2A37C8 | 84C0                     | test al,al                              |
00007FF71E2A37CA | 0F84 16010000            | je tauri-app.7FF71E2A38E6               |
00007FF71E2A37D0 | 48:8D83 08020000         | lea rax,qword ptr ds:[rbx+208]          |
00007FF71E2A37D7 | 4C:8B8B 88030000         | mov r9,qword ptr ds:[rbx+388]           |
00007FF71E2A37DE | 4C:8B93 90030000         | mov r10,qword ptr ds:[rbx+390]          |
00007FF71E2A37E5 | 48:8B8B A8030000         | mov rcx,qword ptr ds:[rbx+3A8]          |
00007FF71E2A37EC | 48:8D9424 206A0000       | lea rdx,qword ptr ss:[rsp+6A20]         |
00007FF71E2A37F4 | 48:898A 18020000         | mov qword ptr ds:[rdx+218],rcx          |
00007FF71E2A37FB | 0F1083 98030000          | movups xmm0,xmmword ptr ds:[rbx+398]    |
00007FF71E2A3802 | 0F1182 08020000          | movups xmmword ptr ds:[rdx+208],xmm0    |
00007FF71E2A3809 | B9 08020000              | mov ecx,208                             |
00007FF71E2A380E | 48:89D7                  | mov rdi,rdx                             |
00007FF71E2A3811 | 48:89DE                  | mov rsi,rbx                             |
00007FF71E2A3814 | F3:A4                    | rep movsb                               |
00007FF71E2A3816 | 4C:8D8424 580A0000       | lea r8,qword ptr ss:[rsp+A58]           |
00007FF71E2A381E | B9 50040000              | mov ecx,450                             |
00007FF71E2A3823 | 4C:89C7                  | mov rdi,r8                              |
00007FF71E2A3826 | 48:89D6                  | mov rsi,rdx                             |
00007FF71E2A3829 | F3:A4                    | rep movsb                               |
00007FF71E2A382B | 45:31DB                  | xor r11d,r11d                           |
00007FF71E2A382E | 45:8898 50040000         | mov byte ptr ds:[r8+450],r11b           |
00007FF71E2A3835 | 48:8D9424 D0080000       | lea rdx,qword ptr ss:[rsp+8D0]          |
00007FF71E2A383D | B9 68010000              | mov ecx,168                             |
00007FF71E2A3842 | 48:89D7                  | mov rdi,rdx                             |
00007FF71E2A3845 | 48:89C6                  | mov rsi,rax                             |
00007FF71E2A3848 | F3:A4                    | rep movsb                               |
00007FF71E2A384A | 4D:8948 F8               | mov qword ptr ds:[r8-8],r9              |
00007FF71E2A384E | 0F1083 70030000          | movups xmm0,xmmword ptr ds:[rbx+370]    |
00007FF71E2A3855 | 41:0F1140 E0             | movups xmmword ptr ds:[r8-20],xmm0      |
00007FF71E2A385A | 48:8B83 80030000         | mov rax,qword ptr ds:[rbx+380]          |
00007FF71E2A3861 | 49:8940 F0               | mov qword ptr ds:[r8-10],rax            |
00007FF71E2A3865 | 4C:8992 380A0000         | mov qword ptr ds:[rdx+A38],r10          |
00007FF71E2A386C | 44:889A 400A0000         | mov byte ptr ds:[rdx+A40],r11b          |
00007FF71E2A3873 | E8 075EE8FF              | call tauri-app.7FF71E12967F             |
00007FF71E2A3878 | 833D 213E7A00 02         | cmp dword ptr ds:[7FF71EA476A0],2       |
00007FF71E2A387F | 0F85 60010000            | jne tauri-app.7FF71E2A39E5              |
00007FF71E2A3885 | 48:8B15 043E7A00         | mov rdx,qword ptr ds:[7FF71EA47690]     |
00007FF71E2A388C | 4C:8B05 053E7A00         | mov r8,qword ptr ds:[7FF71EA47698]      |
00007FF71E2A3893 | 48:8DBC24 30010000       | lea rdi,qword ptr ss:[rsp+130]          | [rsp+130]:sub_7FF71E191E83+5C
00007FF71E2A389B | 48:89F9                  | mov rcx,rdi                             |
00007FF71E2A389E | E8 13490B00              | call <tauri-app.sub_7FF71E3581B6>       |
00007FF71E2A38A3 | 48:8D15 E6437000         | lea rdx,qword ptr ds:[7FF71E9A7C90]     | 00007FF71E9A7C90:&"/build\\source\\repos\\volt\\volt-monorepo\\apps\\desktop-interface\\.cargo-home\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tauri-2.9.2\\src\\async_runtime.rs"
00007FF71E2A38AA | E9 5B010000              | jmp tauri-app.7FF71E2A3A0A              |
00007FF71E2A38AF | 48:8B15 1A3E7A00         | mov rdx,qword ptr ds:[7FF71EA476D0]     |
00007FF71E2A38B6 | 4C:8B05 1B3E7A00         | mov r8,qword ptr ds:[7FF71EA476D8]      |
00007FF71E2A38BD | 48:8DBC24 30010000       | lea rdi,qword ptr ss:[rsp+130]          | [rsp+130]:sub_7FF71E191E83+5C
00007FF71E2A38C5 | 48:89F9                  | mov rcx,rdi                             |
00007FF71E2A38C8 | E8 E9480B00              | call <tauri-app.sub_7FF71E3581B6>       |
00007FF71E2A38CD | 48:8D15 D4437000         | lea rdx,qword ptr ds:[7FF71E9A7CA8]     | 00007FF71E9A7CA8:&"/build\\source\\repos\\volt\\volt-monorepo\\apps\\desktop-interface\\.cargo-home\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tauri-2.9.2\\src\\async_runtime.rs"
00007FF71E2A38D4 | 48:8D8C24 D0080000       | lea rcx,qword ptr ss:[rsp+8D0]          |
00007FF71E2A38DC | E8 03EC0200              | call <tauri-app.sub_7FF71E2D24E4>       |
00007FF71E2A38E1 | E9 8F090000              | jmp tauri-app.7FF71E2A4275              |
00007FF71E2A38E6 | 4C:8D05 20A02B00         | lea r8,qword ptr ds:[7FF71E55D90D]      | 00007FF71E55D90D:"save_file_to_scriptscreate_directorydirectory_existsdelete_directoryrename_directorylist_files_in_directorylist_directory_entriesget_scripts_directory_cmdget_autoexec_directory_cmdget_workspace_directory_cmdopen_folder_in_explorerensure_ignore_folderget_client_settingsupdate_client_settingsget_roblox_path_cmdget_validated_roblox_path_cmdvalidate_roblox_path_cmdroblox_exists_cmdget_roblox_exe_path_cmdget_roblox_version_cmdpick_roblox_directoryvalidate_and_update_roblox_pathget_volt_bin_ve
00007FF71E2A38ED | 41:B9 14000000           | mov r9d,14                              |
00007FF71E2A38F3 | 48:89F1                  | mov rcx,rsi                             |
00007FF71E2A38F6 | 48:89FA                  | mov rdx,rdi                             |
00007FF71E2A38F9 | E8 670DC8FF              | call <tauri-app.sub_7FF71DF24665>       |
00007FF71E2A38FE | 84C0                     | test al,al                              |
00007FF71E2A3900 | 0F84 16010000            | je tauri-app.7FF71E2A3A1C               |
00007FF71E2A3906 | 48:8D83 08020000         | lea rax,qword ptr ds:[rbx+208]          |
00007FF71E2A390D | 4C:8B8B 88030000         | mov r9,qword ptr ds:[rbx+388]           |
00007FF71E2A3914 | 4C:8B93 90030000         | mov r10,qword ptr ds:[rbx+390]          |
00007FF71E2A391B | 48:8B8B A8030000         | mov rcx,qword ptr ds:[rbx+3A8]          |
00007FF71E2A3922 | 48:8D9424 206A0000       | lea rdx,qword ptr ss:[rsp+6A20]         |
00007FF71E2A392A | 48:898A 18020000         | mov qword ptr ds:[rdx+218],rcx          |
00007FF71E2A3931 | 0F1083 98030000          | movups xmm0,xmmword ptr ds:[rbx+398]    |
00007FF71E2A3938 | 0F1182 08020000          | movups xmmword ptr ds:[rdx+208],xmm0    |
00007FF71E2A393F | B9 08020000              | mov ecx,208                             |
00007FF71E2A3944 | 48:89D7                  | mov rdi,rdx                             |
00007FF71E2A3947 | 48:89DE                  | mov rsi,rbx                             |
00007FF71E2A394A | F3:A4                    | rep movsb                               |
00007FF71E2A394C | 4C:8D8424 580A0000       | lea r8,qword ptr ss:[rsp+A58]           |
00007FF71E2A3954 | B9 00060000              | mov ecx,600                             |
00007FF71E2A3959 | 4C:89C7                  | mov rdi,r8                              |
00007FF71E2A395C | 48:89D6                  | mov rsi,rdx                             |
00007FF71E2A395F | F3:A4                    | rep movsb                               |
00007FF71E2A3961 | 45:31DB                  | xor r11d,r11d                           |
00007FF71E2A3964 | 45:8898 00060000         | mov byte ptr ds:[r8+600],r11b           |
00007FF71E2A396B | 48:8D9424 D0080000       | lea rdx,qword ptr ss:[rsp+8D0]          |
00007FF71E2A3973 | B9 68010000              | mov ecx,168                             |
00007FF71E2A3978 | 48:89D7                  | mov rdi,rdx                             |
00007FF71E2A397B | 48:89C6                  | mov rsi,rax                             |
00007FF71E2A397E | F3:A4                    | rep movsb                               |
00007FF71E2A3980 | 4D:8948 F8               | mov qword ptr ds:[r8-8],r9              |
00007FF71E2A3984 | 0F1083 70030000          | movups xmm0,xmmword ptr ds:[rbx+370]    |
00007FF71E2A398B | 41:0F1140 E0             | movups xmmword ptr ds:[r8-20],xmm0      |
00007FF71E2A3990 | 48:8B83 80030000         | mov rax,qword ptr ds:[rbx+380]          |
00007FF71E2A3997 | 49:8940 F0               | mov qword ptr ds:[r8-10],rax            |
00007FF71E2A399B | 4C:8992 980D0000         | mov qword ptr ds:[rdx+D98],r10          |
00007FF71E2A39A2 | 44:889A A00D0000         | mov byte ptr ds:[rdx+DA0],r11b          |
00007FF71E2A39A9 | E8 D15CE8FF              | call tauri-app.7FF71E12967F             |
00007FF71E2A39AE | 833D EB3C7A00 02         | cmp dword ptr ds:[7FF71EA476A0],2       |
00007FF71E2A39B5 | 0F85 60010000            | jne tauri-app.7FF71E2A3B1B              |
00007FF71E2A39BB | 48:8B15 CE3C7A00         | mov rdx,qword ptr ds:[7FF71EA47690]     |
00007FF71E2A39C2 | 4C:8B05 CF3C7A00         | mov r8,qword ptr ds:[7FF71EA47698]      |
00007FF71E2A39C9 | 48:8DBC24 30010000       | lea rdi,qword ptr ss:[rsp+130]          | [rsp+130]:sub_7FF71E191E83+5C
00007FF71E2A39D1 | 48:89F9                  | mov rcx,rdi                             |
00007FF71E2A39D4 | E8 DD470B00              | call <tauri-app.sub_7FF71E3581B6>       |
00007FF71E2A39D9 | 48:8D15 B0427000         | lea rdx,qword ptr ds:[7FF71E9A7C90]     | 00007FF71E9A7C90:&"/build\\source\\repos\\volt\\volt-monorepo\\apps\\desktop-interface\\.cargo-home\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tauri-2.9.2\\src\\async_runtime.rs"
00007FF71E2A39E0 | E9 5B010000              | jmp tauri-app.7FF71E2A3B40              |
00007FF71E2A39E5 | 48:8B15 E43C7A00         | mov rdx,qword ptr ds:[7FF71EA476D0]     |
00007FF71E2A39EC | 4C:8B05 E53C7A00         | mov r8,qword ptr ds:[7FF71EA476D8]      |
00007FF71E2A39F3 | 48:8DBC24 30010000       | lea rdi,qword ptr ss:[rsp+130]          | [rsp+130]:sub_7FF71E191E83+5C
00007FF71E2A39FB | 48:89F9                  | mov rcx,rdi                             |
00007FF71E2A39FE | E8 B3470B00              | call <tauri-app.sub_7FF71E3581B6>       |
00007FF71E2A3A03 | 48:8D15 9E427000         | lea rdx,qword ptr ds:[7FF71E9A7CA8]     | 00007FF71E9A7CA8:&"/build\\source\\repos\\volt\\volt-monorepo\\apps\\desktop-interface\\.cargo-home\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tauri-2.9.2\\src\\async_runtime.rs"
00007FF71E2A3A0A | 48:8D8C24 D0080000       | lea rcx,qword ptr ss:[rsp+8D0]          |
00007FF71E2A3A12 | E8 62D00200              | call <tauri-app.sub_7FF71E2D0A79>       |
00007FF71E2A3A17 | E9 59080000              | jmp tauri-app.7FF71E2A4275              |
00007FF71E2A3A1C | 4C:8D05 FE9E2B00         | lea r8,qword ptr ds:[7FF71E55D921]      | 00007FF71E55D921:"create_directorydirectory_existsdelete_directoryrename_directorylist_files_in_directorylist_directory_entriesget_scripts_directory_cmdget_autoexec_directory_cmdget_workspace_directory_cmdopen_folder_in_explorerensure_ignore_folderget_client_settingsupdate_client_settingsget_roblox_path_cmdget_validated_roblox_path_cmdvalidate_roblox_path_cmdroblox_exists_cmdget_roblox_exe_path_cmdget_roblox_version_cmdpick_roblox_directoryvalidate_and_update_roblox_pathget_volt_bin_versionget_volt_bin_ve
00007FF71E2A3A23 | 41:B9 10000000           | mov r9d,10                              |
00007FF71E2A3A29 | 48:89F1                  | mov rcx,rsi                             |
00007FF71E2A3A2C | 48:89FA                  | mov rdx,rdi                             |
00007FF71E2A3A2F | E8 310CC8FF              | call <tauri-app.sub_7FF71DF24665>       |
00007FF71E2A3A34 | 84C0                     | test al,al                              |
00007FF71E2A3A36 | 0F84 16010000            | je tauri-app.7FF71E2A3B52               |
00007FF71E2A3A3C | 48:8D83 08020000         | lea rax,qword ptr ds:[rbx+208]          |
00007FF71E2A3A43 | 4C:8B8B 88030000         | mov r9,qword ptr ds:[rbx+388]           |
00007FF71E2A3A4A | 4C:8B93 90030000         | mov r10,qword ptr ds:[rbx+390]          |
00007FF71E2A3A51 | 48:8B8B A8030000         | mov rcx,qword ptr ds:[rbx+3A8]          |
00007FF71E2A3A58 | 48:8D9424 206A0000       | lea rdx,qword ptr ss:[rsp+6A20]         |
00007FF71E2A3A60 | 48:898A 18020000         | mov qword ptr ds:[rdx+218],rcx          |
00007FF71E2A3A67 | 0F1083 98030000          | movups xmm0,xmmword ptr ds:[rbx+398]    |
00007FF71E2A3A6E | 0F1182 08020000          | movups xmmword ptr ds:[rdx+208],xmm0    |
00007FF71E2A3A75 | B9 08020000              | mov ecx,208                             |
00007FF71E2A3A7A | 48:89D7                  | mov rdi,rdx                             |
00007FF71E2A3A7D | 48:89DE                  | mov rsi,rbx                             |
00007FF71E2A3A80 | F3:A4                    | rep movsb                               |
00007FF71E2A3A82 | 4C:8D8424 580A0000       | lea r8,qword ptr ss:[rsp+A58]           |
00007FF71E2A3A8A | B9 A8030000              | mov ecx,3A8                             |
00007FF71E2A3A8F | 4C:89C7                  | mov rdi,r8                              |
00007FF71E2A3A92 | 48:89D6                  | mov rsi,rdx                             |
00007FF71E2A3A95 | F3:A4                    | rep movsb                               |
00007FF71E2A3A97 | 45:31DB                  | xor r11d,r11d                           |
00007FF71E2A3A9A | 45:8898 A8030000         | mov byte ptr ds:[r8+3A8],r11b           |
00007FF71E2A3AA1 | 48:8D9424 D0080000       | lea rdx,qword ptr ss:[rsp+8D0]          |
00007FF71E2A3AA9 | B9 68010000              | mov ecx,168                             |
00007FF71E2A3AAE | 48:89D7                  | mov rdi,rdx                             |
00007FF71E2A3AB1 | 48:89C6                  | mov rsi,rax                             |
00007FF71E2A3AB4 | F3:A4                    | rep movsb                               |
00007FF71E2A3AB6 | 4D:8948 F8               | mov qword ptr ds:[r8-8],r9              |
00007FF71E2A3ABA | 0F1083 70030000          | movups xmm0,xmmword ptr ds:[rbx+370]    |
00007FF71E2A3AC1 | 41:0F1140 E0             | movups xmmword ptr ds:[r8-20],xmm0      |
00007FF71E2A3AC6 | 48:8B83 80030000         | mov rax,qword ptr ds:[rbx+380]          |
00007FF71E2A3ACD | 49:8940 F0               | mov qword ptr ds:[r8-10],rax            |
00007FF71E2A3AD1 | 4C:8992 E8080000         | mov qword ptr ds:[rdx+8E8],r10          |
00007FF71E2A3AD8 | 44:889A F0080000         | mov byte ptr ds:[rdx+8F0],r11b          |
00007FF71E2A3ADF | E8 9B5BE8FF              | call tauri-app.7FF71E12967F             |
00007FF71E2A3AE4 | 833D B53B7A00 02         | cmp dword ptr ds:[7FF71EA476A0],2       |
00007FF71E2A3AEB | 0F85 60010000            | jne tauri-app.7FF71E2A3C51              |
00007FF71E2A3AF1 | 48:8B15 983B7A00         | mov rdx,qword ptr ds:[7FF71EA47690]     |
00007FF71E2A3AF8 | 4C:8B05 993B7A00         | mov r8,qword ptr ds:[7FF71EA47698]      |
00007FF71E2A3AFF | 48:8DBC24 30010000       | lea rdi,qword ptr ss:[rsp+130]          | [rsp+130]:sub_7FF71E191E83+5C
00007FF71E2A3B07 | 48:89F9                  | mov rcx,rdi                             |
00007FF71E2A3B0A | E8 A7460B00              | call <tauri-app.sub_7FF71E3581B6>       |
00007FF71E2A3B0F | 48:8D15 7A417000         | lea rdx,qword ptr ds:[7FF71E9A7C90]     | 00007FF71E9A7C90:&"/build\\source\\repos\\volt\\volt-monorepo\\apps\\desktop-interface\\.cargo-home\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tauri-2.9.2\\src\\async_runtime.rs"
00007FF71E2A3B16 | E9 5B010000              | jmp tauri-app.7FF71E2A3C76              |
00007FF71E2A3B1B | 48:8B15 AE3B7A00         | mov rdx,qword ptr ds:[7FF71EA476D0]     |
00007FF71E2A3B22 | 4C:8B05 AF3B7A00         | mov r8,qword ptr ds:[7FF71EA476D8]      |
00007FF71E2A3B29 | 48:8DBC24 30010000       | lea rdi,qword ptr ss:[rsp+130]          | [rsp+130]:sub_7FF71E191E83+5C
00007FF71E2A3B31 | 48:89F9                  | mov rcx,rdi                             |
00007FF71E2A3B34 | E8 7D460B00              | call <tauri-app.sub_7FF71E3581B6>       |
00007FF71E2A3B39 | 48:8D15 68417000         | lea rdx,qword ptr ds:[7FF71E9A7CA8]     | 00007FF71E9A7CA8:&"/build\\source\\repos\\volt\\volt-monorepo\\apps\\desktop-interface\\.cargo-home\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tauri-2.9.2\\src\\async_runtime.rs"
00007FF71E2A3B40 | 48:8D8C24 D0080000       | lea rcx,qword ptr ss:[rsp+8D0]          |
00007FF71E2A3B48 | E8 96B40200              | call tauri-app.7FF71E2CEFE3             |
00007FF71E2A3B4D | E9 23070000              | jmp tauri-app.7FF71E2A4275              |
00007FF71E2A3B52 | 4C:8D05 D89D2B00         | lea r8,qword ptr ds:[7FF71E55D931]      | 00007FF71E55D931:"directory_existsdelete_directoryrename_directorylist_files_in_directorylist_directory_entriesget_scripts_directory_cmdget_autoexec_directory_cmdget_workspace_directory_cmdopen_folder_in_explorerensure_ignore_folderget_client_settingsupdate_client_settingsget_roblox_path_cmdget_validated_roblox_path_cmdvalidate_roblox_path_cmdroblox_exists_cmdget_roblox_exe_path_cmdget_roblox_version_cmdpick_roblox_directoryvalidate_and_update_roblox_pathget_volt_bin_versionget_volt_bin_version_infoget_fi
00007FF71E2A3B59 | 41:B9 10000000           | mov r9d,10                              |
00007FF71E2A3B5F | 48:89F1                  | mov rcx,rsi                             |
00007FF71E2A3B62 | 48:89FA                  | mov rdx,rdi                             |
00007FF71E2A3B65 | E8 FB0AC8FF              | call <tauri-app.sub_7FF71DF24665>       |
00007FF71E2A3B6A | 84C0                     | test al,al                              |
00007FF71E2A3B6C | 0F84 16010000            | je tauri-app.7FF71E2A3C88               |
00007FF71E2A3B72 | 48:8D83 08020000         | lea rax,qword ptr ds:[rbx+208]          |
00007FF71E2A3B79 | 4C:8B8B 88030000         | mov r9,qword ptr ds:[rbx+388]           |
00007FF71E2A3B80 | 4C:8B93 90030000         | mov r10,qword ptr ds:[rbx+390]          |
00007FF71E2A3B87 | 48:8B8B A8030000         | mov rcx,qword ptr ds:[rbx+3A8]          |
00007FF71E2A3B8E | 48:8D9424 206A0000       | lea rdx,qword ptr ss:[rsp+6A20]         |
00007FF71E2A3B96 | 48:898A 18020000         | mov qword ptr ds:[rdx+218],rcx          |
00007FF71E2A3B9D | 0F1083 98030000          | movups xmm0,xmmword ptr ds:[rbx+398]    |
00007FF71E2A3BA4 | 0F1182 08020000          | movups xmmword ptr ds:[rdx+208],xmm0    |
00007FF71E2A3BAB | B9 08020000              | mov ecx,208                             |
00007FF71E2A3BB0 | 48:89D7                  | mov rdi,rdx                             |
00007FF71E2A3BB3 | 48:89DE                  | mov rsi,rbx                             |
00007FF71E2A3BB6 | F3:A4                    | rep movsb                               |
00007FF71E2A3BB8 | 4C:8D8424 580A0000       | lea r8,qword ptr ss:[rsp+A58]           |
00007FF71E2A3BC0 | B9 88020000              | mov ecx,288                             |
00007FF71E2A3BC5 | 4C:89C7                  | mov rdi,r8                              |
00007FF71E2A3BC8 | 48:89D6                  | mov rsi,rdx                             |
00007FF71E2A3BCB | F3:A4                    | rep movsb                               |
00007FF71E2A3BCD | 45:31DB                  | xor r11d,r11d                           |
00007FF71E2A3BD0 | 45:8898 88020000         | mov byte ptr ds:[r8+288],r11b           |
00007FF71E2A3BD7 | 48:8D9424 D0080000       | lea rdx,qword ptr ss:[rsp+8D0]          |
00007FF71E2A3BDF | B9 68010000              | mov ecx,168                             |
00007FF71E2A3BE4 | 48:89D7                  | mov rdi,rdx                             |
00007FF71E2A3BE7 | 48:89C6                  | mov rsi,rax                             |
00007FF71E2A3BEA | F3:A4                    | rep movsb                               |
00007FF71E2A3BEC | 4D:8948 F8               | mov qword ptr ds:[r8-8],r9              |
00007FF71E2A3BF0 | 0F1083 70030000          | movups xmm0,xmmword ptr ds:[rbx+370]    |
00007FF71E2A3BF7 | 41:0F1140 E0             | movups xmmword ptr ds:[r8-20],xmm0      |
00007FF71E2A3BFC | 48:8B83 80030000         | mov rax,qword ptr ds:[rbx+380]          |
00007FF71E2A3C03 | 49:8940 F0               | mov qword ptr ds:[r8-10],rax            |
00007FF71E2A3C07 | 4C:8992 A8060000         | mov qword ptr ds:[rdx+6A8],r10          |
00007FF71E2A3C0E | 44:889A B0060000         | mov byte ptr ds:[rdx+6B0],r11b          |
00007FF71E2A3C15 | E8 655AE8FF              | call tauri-app.7FF71E12967F             |
00007FF71E2A3C1A | 833D 7F3A7A00 02         | cmp dword ptr ds:[7FF71EA476A0],2       |
00007FF71E2A3C21 | 0F85 60010000            | jne tauri-app.7FF71E2A3D87              |
00007FF71E2A3C27 | 48:8B15 623A7A00         | mov rdx,qword ptr ds:[7FF71EA47690]     |
00007FF71E2A3C2E | 4C:8B05 633A7A00         | mov r8,qword ptr ds:[7FF71EA47698]      |
00007FF71E2A3C35 | 48:8DBC24 30010000       | lea rdi,qword ptr ss:[rsp+130]          | [rsp+130]:sub_7FF71E191E83+5C
00007FF71E2A3C3D | 48:89F9                  | mov rcx,rdi                             |
00007FF71E2A3C40 | E8 71450B00              | call <tauri-app.sub_7FF71E3581B6>       |
00007FF71E2A3C45 | 48:8D15 44407000         | lea rdx,qword ptr ds:[7FF71E9A7C90]     | 00007FF71E9A7C90:&"/build\\source\\repos\\volt\\volt-monorepo\\apps\\desktop-interface\\.cargo-home\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tauri-2.9.2\\src\\async_runtime.rs"
00007FF71E2A3C4C | E9 5B010000              | jmp tauri-app.7FF71E2A3DAC              |
00007FF71E2A3C51 | 48:8B15 783A7A00         | mov rdx,qword ptr ds:[7FF71EA476D0]     |
00007FF71E2A3C58 | 4C:8B05 793A7A00         | mov r8,qword ptr ds:[7FF71EA476D8]      |
00007FF71E2A3C5F | 48:8DBC24 30010000       | lea rdi,qword ptr ss:[rsp+130]          | [rsp+130]:sub_7FF71E191E83+5C
00007FF71E2A3C67 | 48:89F9                  | mov rcx,rdi                             |
00007FF71E2A3C6A | E8 47450B00              | call <tauri-app.sub_7FF71E3581B6>       |
00007FF71E2A3C6F | 48:8D15 32407000         | lea rdx,qword ptr ds:[7FF71E9A7CA8]     | 00007FF71E9A7CA8:&"/build\\source\\repos\\volt\\volt-monorepo\\apps\\desktop-interface\\.cargo-home\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tauri-2.9.2\\src\\async_runtime.rs"
00007FF71E2A3C76 | 48:8D8C24 D0080000       | lea rcx,qword ptr ss:[rsp+8D0]          |
00007FF71E2A3C7E | E8 47A10200              | call <tauri-app.sub_7FF71E2CDDCA>       |
00007FF71E2A3C83 | E9 ED050000              | jmp tauri-app.7FF71E2A4275              |
00007FF71E2A3C88 | 4C:8D05 B29C2B00         | lea r8,qword ptr ds:[7FF71E55D941]      | 00007FF71E55D941:"delete_directoryrename_directorylist_files_in_directorylist_directory_entriesget_scripts_directory_cmdget_autoexec_directory_cmdget_workspace_directory_cmdopen_folder_in_explorerensure_ignore_folderget_client_settingsupdate_client_settingsget_roblox_path_cmdget_validated_roblox_path_cmdvalidate_roblox_path_cmdroblox_exists_cmdget_roblox_exe_path_cmdget_roblox_version_cmdpick_roblox_directoryvalidate_and_update_roblox_pathget_volt_bin_versionget_volt_bin_version_infoget_file_version_cmddo
00007FF71E2A3C8F | 41:B9 10000000           | mov r9d,10                              |
00007FF71E2A3C95 | 48:89F1                  | mov rcx,rsi                             |
00007FF71E2A3C98 | 48:89FA                  | mov rdx,rdi                             |
00007FF71E2A3C9B | E8 C509C8FF              | call <tauri-app.sub_7FF71DF24665>       |
00007FF71E2A3CA0 | 84C0                     | test al,al                              |
00007FF71E2A3CA2 | 0F84 16010000            | je tauri-app.7FF71E2A3DBE               |
00007FF71E2A3CA8 | 48:8D83 08020000         | lea rax,qword ptr ds:[rbx+208]          |
00007FF71E2A3CAF | 4C:8B8B 88030000         | mov r9,qword ptr ds:[rbx+388]           |
00007FF71E2A3CB6 | 4C:8B93 90030000         | mov r10,qword ptr ds:[rbx+390]          |
00007FF71E2A3CBD | 48:8B8B A8030000         | mov rcx,qword ptr ds:[rbx+3A8]          |
00007FF71E2A3CC4 | 48:8D9424 206A0000       | lea rdx,qword ptr ss:[rsp+6A20]         |
00007FF71E2A3CCC | 48:898A 18020000         | mov qword ptr ds:[rdx+218],rcx          |
00007FF71E2A3CD3 | 0F1083 98030000          | movups xmm0,xmmword ptr ds:[rbx+398]    |
00007FF71E2A3CDA | 0F1182 08020000          | movups xmmword ptr ds:[rdx+208],xmm0    |
00007FF71E2A3CE1 | B9 08020000              | mov ecx,208                             |
00007FF71E2A3CE6 | 48:89D7                  | mov rdi,rdx                             |
00007FF71E2A3CE9 | 48:89DE                  | mov rsi,rbx                             |
00007FF71E2A3CEC | F3:A4                    | rep movsb                               |
00007FF71E2A3CEE | 4C:8D8424 580A0000       | lea r8,qword ptr ss:[rsp+A58]           |
00007FF71E2A3CF6 | B9 08040000              | mov ecx,408                             |
00007FF71E2A3CFB | 4C:89C7                  | mov rdi,r8                              |
00007FF71E2A3CFE | 48:89D6                  | mov rsi,rdx                             |
00007FF71E2A3D01 | F3:A4                    | rep movsb                               |
00007FF71E2A3D03 | 45:31DB                  | xor r11d,r11d                           |
00007FF71E2A3D06 | 45:8898 08040000         | mov byte ptr ds:[r8+408],r11b           |
00007FF71E2A3D0D | 48:8D9424 D0080000       | lea rdx,qword ptr ss:[rsp+8D0]          |
00007FF71E2A3D15 | B9 68010000              | mov ecx,168                             |
00007FF71E2A3D1A | 48:89D7                  | mov rdi,rdx                             |
00007FF71E2A3D1D | 48:89C6                  | mov rsi,rax                             |
00007FF71E2A3D20 | F3:A4                    | rep movsb                               |
00007FF71E2A3D22 | 4D:8948 F8               | mov qword ptr ds:[r8-8],r9              |
00007FF71E2A3D26 | 0F1083 70030000          | movups xmm0,xmmword ptr ds:[rbx+370]    |
00007FF71E2A3D2D | 41:0F1140 E0             | movups xmmword ptr ds:[r8-20],xmm0      |
00007FF71E2A3D32 | 48:8B83 80030000         | mov rax,qword ptr ds:[rbx+380]          |
00007FF71E2A3D39 | 49:8940 F0               | mov qword ptr ds:[r8-10],rax            |
00007FF71E2A3D3D | 4C:8992 A8090000         | mov qword ptr ds:[rdx+9A8],r10          |
00007FF71E2A3D44 | 44:889A B0090000         | mov byte ptr ds:[rdx+9B0],r11b          |
00007FF71E2A3D4B | E8 2F59E8FF              | call tauri-app.7FF71E12967F             |
00007FF71E2A3D50 | 833D 49397A00 02         | cmp dword ptr ds:[7FF71EA476A0],2       |
00007FF71E2A3D57 | 0F85 60010000            | jne tauri-app.7FF71E2A3EBD              |
00007FF71E2A3D5D | 48:8B15 2C397A00         | mov rdx,qword ptr ds:[7FF71EA47690]     |
00007FF71E2A3D64 | 4C:8B05 2D397A00         | mov r8,qword ptr ds:[7FF71EA47698]      |
00007FF71E2A3D6B | 48:8DBC24 30010000       | lea rdi,qword ptr ss:[rsp+130]          | [rsp+130]:sub_7FF71E191E83+5C
00007FF71E2A3D73 | 48:89F9                  | mov rcx,rdi                             |
00007FF71E2A3D76 | E8 3B440B00              | call <tauri-app.sub_7FF71E3581B6>       |
00007FF71E2A3D7B | 48:8D15 0E3F7000         | lea rdx,qword ptr ds:[7FF71E9A7C90]     | 00007FF71E9A7C90:&"/build\\source\\repos\\volt\\volt-monorepo\\apps\\desktop-interface\\.cargo-home\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tauri-2.9.2\\src\\async_runtime.rs"
00007FF71E2A3D82 | E9 5B010000              | jmp tauri-app.7FF71E2A3EE2              |
00007FF71E2A3D87 | 48:8B15 42397A00         | mov rdx,qword ptr ds:[7FF71EA476D0]     |
00007FF71E2A3D8E | 4C:8B05 43397A00         | mov r8,qword ptr ds:[7FF71EA476D8]      |
00007FF71E2A3D95 | 48:8DBC24 30010000       | lea rdi,qword ptr ss:[rsp+130]          | [rsp+130]:sub_7FF71E191E83+5C
00007FF71E2A3D9D | 48:89F9                  | mov rcx,rdi                             |
00007FF71E2A3DA0 | E8 11440B00              | call <tauri-app.sub_7FF71E3581B6>       |
00007FF71E2A3DA5 | 48:8D15 FC3E7000         | lea rdx,qword ptr ds:[7FF71E9A7CA8]     | 00007FF71E9A7CA8:&"/build\\source\\repos\\volt\\volt-monorepo\\apps\\desktop-interface\\.cargo-home\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tauri-2.9.2\\src\\async_runtime.rs"
00007FF71E2A3DAC | 48:8D8C24 D0080000       | lea rcx,qword ptr ss:[rsp+8D0]          |
00007FF71E2A3DB4 | E8 15950200              | call <tauri-app.sub_7FF71E2CD2CE>       |
00007FF71E2A3DB9 | E9 B7040000              | jmp tauri-app.7FF71E2A4275              |
00007FF71E2A3DBE | 4C:8D05 8C9B2B00         | lea r8,qword ptr ds:[7FF71E55D951]      | 00007FF71E55D951:"rename_directorylist_files_in_directorylist_directory_entriesget_scripts_directory_cmdget_autoexec_directory_cmdget_workspace_directory_cmdopen_folder_in_explorerensure_ignore_folderget_client_settingsupdate_client_settingsget_roblox_path_cmdget_validated_roblox_path_cmdvalidate_roblox_path_cmdroblox_exists_cmdget_roblox_exe_path_cmdget_roblox_version_cmdpick_roblox_directoryvalidate_and_update_roblox_pathget_volt_bin_versionget_volt_bin_version_infoget_file_version_cmddownload_file_from
00007FF71E2A3DC5 | 41:B9 10000000           | mov r9d,10                              |
00007FF71E2A3DCB | 48:89F1                  | mov rcx,rsi                             |
00007FF71E2A3DCE | 48:89FA                  | mov rdx,rdi                             |
00007FF71E2A3DD1 | E8 8F08C8FF              | call <tauri-app.sub_7FF71DF24665>       |
00007FF71E2A3DD6 | 84C0                     | test al,al                              |
00007FF71E2A3DD8 | 0F84 16010000            | je tauri-app.7FF71E2A3EF4               |
00007FF71E2A3DDE | 48:8D83 08020000         | lea rax,qword ptr ds:[rbx+208]          |
00007FF71E2A3DE5 | 4C:8B8B 88030000         | mov r9,qword ptr ds:[rbx+388]           |
00007FF71E2A3DEC | 4C:8B93 90030000         | mov r10,qword ptr ds:[rbx+390]          |
00007FF71E2A3DF3 | 48:8B8B A8030000         | mov rcx,qword ptr ds:[rbx+3A8]          |
00007FF71E2A3DFA | 48:8D9424 206A0000       | lea rdx,qword ptr ss:[rsp+6A20]         |
00007FF71E2A3E02 | 48:898A 18020000         | mov qword ptr ds:[rdx+218],rcx          |
00007FF71E2A3E09 | 0F1083 98030000          | movups xmm0,xmmword ptr ds:[rbx+398]    |
00007FF71E2A3E10 | 0F1182 08020000          | movups xmmword ptr ds:[rdx+208],xmm0    |
00007FF71E2A3E17 | B9 08020000              | mov ecx,208                             |
00007FF71E2A3E1C | 48:89D7                  | mov rdi,rdx                             |
00007FF71E2A3E1F | 48:89DE                  | mov rsi,rbx                             |
00007FF71E2A3E22 | F3:A4                    | rep movsb                               |
00007FF71E2A3E24 | 4C:8D8424 580A0000       | lea r8,qword ptr ss:[rsp+A58]           |
00007FF71E2A3E2C | B9 88050000              | mov ecx,588                             |
00007FF71E2A3E31 | 4C:89C7                  | mov rdi,r8                              |
00007FF71E2A3E34 | 48:89D6                  | mov rsi,rdx                             |
00007FF71E2A3E37 | F3:A4                    | rep movsb                               |
00007FF71E2A3E39 | 45:31DB                  | xor r11d,r11d                           |
00007FF71E2A3E3C | 45:8898 88050000         | mov byte ptr ds:[r8+588],r11b           |
00007FF71E2A3E43 | 48:8D9424 D0080000       | lea rdx,qword ptr ss:[rsp+8D0]          |
00007FF71E2A3E4B | B9 68010000              | mov ecx,168                             |
00007FF71E2A3E50 | 48:89D7                  | mov rdi,rdx                             |
00007FF71E2A3E53 | 48:89C6                  | mov rsi,rax                             |
00007FF71E2A3E56 | F3:A4                    | rep movsb                               |
00007FF71E2A3E58 | 4D:8948 F8               | mov qword ptr ds:[r8-8],r9              |
00007FF71E2A3E5C | 0F1083 70030000          | movups xmm0,xmmword ptr ds:[rbx+370]    |
00007FF71E2A3E63 | 41:0F1140 E0             | movups xmmword ptr ds:[r8-20],xmm0      |
00007FF71E2A3E68 | 48:8B83 80030000         | mov rax,qword ptr ds:[rbx+380]          |
00007FF71E2A3E6F | 49:8940 F0               | mov qword ptr ds:[r8-10],rax            |
00007FF71E2A3E73 | 4C:8992 A80C0000         | mov qword ptr ds:[rdx+CA8],r10          |
00007FF71E2A3E7A | 44:889A B00C0000         | mov byte ptr ds:[rdx+CB0],r11b          |
00007FF71E2A3E81 | E8 F957E8FF              | call tauri-app.7FF71E12967F             |
00007FF71E2A3E86 | 833D 13387A00 02         | cmp dword ptr ds:[7FF71EA476A0],2       |
00007FF71E2A3E8D | 0F85 60010000            | jne tauri-app.7FF71E2A3FF3              |
00007FF71E2A3E93 | 48:8B15 F6377A00         | mov rdx,qword ptr ds:[7FF71EA47690]     |
00007FF71E2A3E9A | 4C:8B05 F7377A00         | mov r8,qword ptr ds:[7FF71EA47698]      |
00007FF71E2A3EA1 | 48:8DBC24 30010000       | lea rdi,qword ptr ss:[rsp+130]          | [rsp+130]:sub_7FF71E191E83+5C
00007FF71E2A3EA9 | 48:89F9                  | mov rcx,rdi                             |
00007FF71E2A3EAC | E8 05430B00              | call <tauri-app.sub_7FF71E3581B6>       |
00007FF71E2A3EB1 | 48:8D15 D83D7000         | lea rdx,qword ptr ds:[7FF71E9A7C90]     | 00007FF71E9A7C90:&"/build\\source\\repos\\volt\\volt-monorepo\\apps\\desktop-interface\\.cargo-home\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tauri-2.9.2\\src\\async_runtime.rs"
00007FF71E2A3EB8 | E9 5B010000              | jmp tauri-app.7FF71E2A4018              |
00007FF71E2A3EBD | 48:8B15 0C387A00         | mov rdx,qword ptr ds:[7FF71EA476D0]     |
00007FF71E2A3EC4 | 4C:8B05 0D387A00         | mov r8,qword ptr ds:[7FF71EA476D8]      |
00007FF71E2A3ECB | 48:8DBC24 30010000       | lea rdi,qword ptr ss:[rsp+130]          | [rsp+130]:sub_7FF71E191E83+5C
00007FF71E2A3ED3 | 48:89F9                  | mov rcx,rdi                             |
00007FF71E2A3ED6 | E8 DB420B00              | call <tauri-app.sub_7FF71E3581B6>       |
00007FF71E2A3EDB | 48:8D15 C63D7000         | lea rdx,qword ptr ds:[7FF71E9A7CA8]     | 00007FF71E9A7CA8:&"/build\\source\\repos\\volt\\volt-monorepo\\apps\\desktop-interface\\.cargo-home\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tauri-2.9.2\\src\\async_runtime.rs"
00007FF71E2A3EE2 | 48:8D8C24 D0080000       | lea rcx,qword ptr ss:[rsp+8D0]          |
00007FF71E2A3EEA | E8 E9810200              | call tauri-app.7FF71E2CC0D8             |
00007FF71E2A3EEF | E9 81030000              | jmp tauri-app.7FF71E2A4275              |
00007FF71E2A3EF4 | 4C:8D05 669A2B00         | lea r8,qword ptr ds:[7FF71E55D961]      | 00007FF71E55D961:"list_files_in_directorylist_directory_entriesget_scripts_directory_cmdget_autoexec_directory_cmdget_workspace_directory_cmdopen_folder_in_explorerensure_ignore_folderget_client_settingsupdate_client_settingsget_roblox_path_cmdget_validated_roblox_path_cmdvalidate_roblox_path_cmdroblox_exists_cmdget_roblox_exe_path_cmdget_roblox_version_cmdpick_roblox_directoryvalidate_and_update_roblox_pathget_volt_bin_versionget_volt_bin_version_infoget_file_version_cmddownload_file_from_url_cmdrestore_
00007FF71E2A3EFB | 41:B9 17000000           | mov r9d,17                              |
00007FF71E2A3F01 | 48:89F1                  | mov rcx,rsi                             |
00007FF71E2A3F04 | 48:89FA                  | mov rdx,rdi                             |
00007FF71E2A3F07 | E8 5907C8FF              | call <tauri-app.sub_7FF71DF24665>       |
00007FF71E2A3F0C | 84C0                     | test al,al                              |
00007FF71E2A3F0E | 0F84 16010000            | je tauri-app.7FF71E2A402A               |
00007FF71E2A3F14 | 48:8D83 08020000         | lea rax,qword ptr ds:[rbx+208]          |
00007FF71E2A3F1B | 4C:8B8B 88030000         | mov r9,qword ptr ds:[rbx+388]           |
00007FF71E2A3F22 | 4C:8B93 90030000         | mov r10,qword ptr ds:[rbx+390]          |
00007FF71E2A3F29 | 48:8B8B A8030000         | mov rcx,qword ptr ds:[rbx+3A8]          |
00007FF71E2A3F30 | 48:8D9424 206A0000       | lea rdx,qword ptr ss:[rsp+6A20]         |
00007FF71E2A3F38 | 48:898A 18020000         | mov qword ptr ds:[rdx+218],rcx          |
00007FF71E2A3F3F | 0F1083 98030000          | movups xmm0,xmmword ptr ds:[rbx+398]    |
00007FF71E2A3F46 | 0F1182 08020000          | movups xmmword ptr ds:[rdx+208],xmm0    |
00007FF71E2A3F4D | B9 08020000              | mov ecx,208                             |
00007FF71E2A3F52 | 48:89D7                  | mov rdi,rdx                             |
00007FF71E2A3F55 | 48:89DE                  | mov rsi,rbx                             |
00007FF71E2A3F58 | F3:A4                    | rep movsb                               |
00007FF71E2A3F5A | 4C:8D8424 580A0000       | lea r8,qword ptr ss:[rsp+A58]           |
00007FF71E2A3F62 | B9 48030000              | mov ecx,348                             |
00007FF71E2A3F67 | 4C:89C7                  | mov rdi,r8                              |
00007FF71E2A3F6A | 48:89D6                  | mov rsi,rdx                             |
00007FF71E2A3F6D | F3:A4                    | rep movsb                               |
00007FF71E2A3F6F | 45:31DB                  | xor r11d,r11d                           |
00007FF71E2A3F72 | 45:8898 48030000         | mov byte ptr ds:[r8+348],r11b           |
00007FF71E2A3F79 | 48:8D9424 D0080000       | lea rdx,qword ptr ss:[rsp+8D0]          |
00007FF71E2A3F81 | B9 68010000              | mov ecx,168                             |
00007FF71E2A3F86 | 48:89D7                  | mov rdi,rdx                             |
00007FF71E2A3F89 | 48:89C6                  | mov rsi,rax                             |
00007FF71E2A3F8C | F3:A4                    | rep movsb                               |
00007FF71E2A3F8E | 4D:8948 F8               | mov qword ptr ds:[r8-8],r9              |
00007FF71E2A3F92 | 0F1083 70030000          | movups xmm0,xmmword ptr ds:[rbx+370]    |
00007FF71E2A3F99 | 41:0F1140 E0             | movups xmmword ptr ds:[r8-20],xmm0      |
00007FF71E2A3F9E | 48:8B83 80030000         | mov rax,qword ptr ds:[rbx+380]          |
00007FF71E2A3FA5 | 49:8940 F0               | mov qword ptr ds:[r8-10],rax            |
00007FF71E2A3FA9 | 4C:8992 28080000         | mov qword ptr ds:[rdx+828],r10          |
00007FF71E2A3FB0 | 44:889A 30080000         | mov byte ptr ds:[rdx+830],r11b          |
00007FF71E2A3FB7 | E8 C356E8FF              | call tauri-app.7FF71E12967F             |
00007FF71E2A3FBC | 833D DD367A00 02         | cmp dword ptr ds:[7FF71EA476A0],2       |
00007FF71E2A3FC3 | 0F85 60010000            | jne tauri-app.7FF71E2A4129              |
00007FF71E2A3FC9 | 48:8B15 C0367A00         | mov rdx,qword ptr ds:[7FF71EA47690]     |
00007FF71E2A3FD0 | 4C:8B05 C1367A00         | mov r8,qword ptr ds:[7FF71EA47698]      |
00007FF71E2A3FD7 | 48:8DBC24 30010000       | lea rdi,qword ptr ss:[rsp+130]          | [rsp+130]:sub_7FF71E191E83+5C
00007FF71E2A3FDF | 48:89F9                  | mov rcx,rdi                             |
00007FF71E2A3FE2 | E8 CF410B00              | call <tauri-app.sub_7FF71E3581B6>       |
00007FF71E2A3FE7 | 48:8D15 A23C7000         | lea rdx,qword ptr ds:[7FF71E9A7C90]     | 00007FF71E9A7C90:&"/build\\source\\repos\\volt\\volt-monorepo\\apps\\desktop-interface\\.cargo-home\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tauri-2.9.2\\src\\async_runtime.rs"
00007FF71E2A3FEE | E9 5B010000              | jmp tauri-app.7FF71E2A414E              |
00007FF71E2A3FF3 | 48:8B15 D6367A00         | mov rdx,qword ptr ds:[7FF71EA476D0]     |
00007FF71E2A3FFA | 4C:8B05 D7367A00         | mov r8,qword ptr ds:[7FF71EA476D8]      |
00007FF71E2A4001 | 48:8DBC24 30010000       | lea rdi,qword ptr ss:[rsp+130]          | [rsp+130]:sub_7FF71E191E83+5C
00007FF71E2A4009 | 48:89F9                  | mov rcx,rdi                             |
00007FF71E2A400C | E8 A5410B00              | call <tauri-app.sub_7FF71E3581B6>       |
00007FF71E2A4011 | 48:8D15 903C7000         | lea rdx,qword ptr ds:[7FF71E9A7CA8]     | 00007FF71E9A7CA8:&"/build\\source\\repos\\volt\\volt-monorepo\\apps\\desktop-interface\\.cargo-home\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tauri-2.9.2\\src\\async_runtime.rs"
00007FF71E2A4018 | 48:8D8C24 D0080000       | lea rcx,qword ptr ss:[rsp+8D0]          |
00007FF71E2A4020 | E8 2A670200              | call <tauri-app.sub_7FF71E2CA74F>       |
00007FF71E2A4025 | E9 4B020000              | jmp tauri-app.7FF71E2A4275              |
00007FF71E2A402A | 4C:8D05 47992B00         | lea r8,qword ptr ds:[7FF71E55D978]      | 00007FF71E55D978:"list_directory_entriesget_scripts_directory_cmdget_autoexec_directory_cmdget_workspace_directory_cmdopen_folder_in_explorerensure_ignore_folderget_client_settingsupdate_client_settingsget_roblox_path_cmdget_validated_roblox_path_cmdvalidate_roblox_path_cmdroblox_exists_cmdget_roblox_exe_path_cmdget_roblox_version_cmdpick_roblox_directoryvalidate_and_update_roblox_pathget_volt_bin_versionget_volt_bin_version_infoget_file_version_cmddownload_file_from_url_cmdrestore_cached_volt_files_cmdca
00007FF71E2A4031 | 41:B9 16000000           | mov r9d,16                              |
00007FF71E2A4037 | 48:89F1                  | mov rcx,rsi                             |
00007FF71E2A403A | 48:89FA                  | mov rdx,rdi                             |
00007FF71E2A403D | E8 2306C8FF              | call <tauri-app.sub_7FF71DF24665>       |
00007FF71E2A4042 | 84C0                     | test al,al                              |
00007FF71E2A4044 | 0F84 16010000            | je tauri-app.7FF71E2A4160               |
00007FF71E2A404A | 48:8D83 08020000         | lea rax,qword ptr ds:[rbx+208]          |
00007FF71E2A4051 | 4C:8B8B 88030000         | mov r9,qword ptr ds:[rbx+388]           |
00007FF71E2A4058 | 4C:8B93 90030000         | mov r10,qword ptr ds:[rbx+390]          |
00007FF71E2A405F | 48:8B8B A8030000         | mov rcx,qword ptr ds:[rbx+3A8]          |
00007FF71E2A4066 | 48:8D9424 206A0000       | lea rdx,qword ptr ss:[rsp+6A20]         |
00007FF71E2A406E | 48:898A 18020000         | mov qword ptr ds:[rdx+218],rcx          |
00007FF71E2A4075 | 0F1083 98030000          | movups xmm0,xmmword ptr ds:[rbx+398]    |
00007FF71E2A407C | 0F1182 08020000          | movups xmmword ptr ds:[rdx+208],xmm0    |
00007FF71E2A4083 | B9 08020000              | mov ecx,208                             |
00007FF71E2A4088 | 48:89D7                  | mov rdi,rdx                             |
00007FF71E2A408B | 48:89DE                  | mov rsi,rbx                             |
00007FF71E2A408E | F3:A4                    | rep movsb                               |
00007FF71E2A4090 | 4C:8D8424 580A0000       | lea r8,qword ptr ss:[rsp+A58]           |
00007FF71E2A4098 | B9 48030000              | mov ecx,348                             |
00007FF71E2A409D | 4C:89C7                  | mov rdi,r8                              |
00007FF71E2A40A0 | 48:89D6                  | mov rsi,rdx                             |
00007FF71E2A40A3 | F3:A4                    | rep movsb                               |
00007FF71E2A40A5 | 45:31DB                  | xor r11d,r11d                           |
00007FF71E2A40A8 | 45:8898 48030000         | mov byte ptr ds:[r8+348],r11b           |
00007FF71E2A40AF | 48:8D9424 D0080000       | lea rdx,qword ptr ss:[rsp+8D0]          |
00007FF71E2A40B7 | B9 68010000              | mov ecx,168                             |
00007FF71E2A40BC | 48:89D7                  | mov rdi,rdx                             |
00007FF71E2A40BF | 48:89C6                  | mov rsi,rax                             |
00007FF71E2A40C2 | F3:A4                    | rep movsb                               |
00007FF71E2A40C4 | 4D:8948 F8               | mov qword ptr ds:[r8-8],r9              |
00007FF71E2A40C8 | 0F1083 70030000          | movups xmm0,xmmword ptr ds:[rbx+370]    |
00007FF71E2A40CF | 41:0F1140 E0             | movups xmmword ptr ds:[r8-20],xmm0      |
00007FF71E2A40D4 | 48:8B83 80030000         | mov rax,qword ptr ds:[rbx+380]          |
00007FF71E2A40DB | 49:8940 F0               | mov qword ptr ds:[r8-10],rax            |
00007FF71E2A40DF | 4C:8992 28080000         | mov qword ptr ds:[rdx+828],r10          |
00007FF71E2A40E6 | 44:889A 30080000         | mov byte ptr ds:[rdx+830],r11b          |
00007FF71E2A40ED | E8 8D55E8FF              | call tauri-app.7FF71E12967F             |
00007FF71E2A40F2 | 833D A7357A00 02         | cmp dword ptr ds:[7FF71EA476A0],2       |
00007FF71E2A40F9 | 0F85 44010000            | jne tauri-app.7FF71E2A4243              |
00007FF71E2A40FF | 48:8B15 8A357A00         | mov rdx,qword ptr ds:[7FF71EA47690]     |
00007FF71E2A4106 | 4C:8B05 8B357A00         | mov r8,qword ptr ds:[7FF71EA47698]      |
00007FF71E2A410D | 48:8DBC24 30010000       | lea rdi,qword ptr ss:[rsp+130]          | [rsp+130]:sub_7FF71E191E83+5C
00007FF71E2A4115 | 48:89F9                  | mov rcx,rdi                             |
00007FF71E2A4118 | E8 99400B00              | call <tauri-app.sub_7FF71E3581B6>       |
00007FF71E2A411D | 48:8D15 6C3B7000         | lea rdx,qword ptr ds:[7FF71E9A7C90]     | 00007FF71E9A7C90:&"/build\\source\\repos\\volt\\volt-monorepo\\apps\\desktop-interface\\.cargo-home\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tauri-2.9.2\\src\\async_runtime.rs"
00007FF71E2A4124 | E9 3F010000              | jmp tauri-app.7FF71E2A4268              |
00007FF71E2A4129 | 48:8B15 A0357A00         | mov rdx,qword ptr ds:[7FF71EA476D0]     |
00007FF71E2A4130 | 4C:8B05 A1357A00         | mov r8,qword ptr ds:[7FF71EA476D8]      |
00007FF71E2A4137 | 48:8DBC24 30010000       | lea rdi,qword ptr ss:[rsp+130]          | [rsp+130]:sub_7FF71E191E83+5C
00007FF71E2A413F | 48:89F9                  | mov rcx,rdi                             |
00007FF71E2A4142 | E8 6F400B00              | call <tauri-app.sub_7FF71E3581B6>       |
00007FF71E2A4147 | 48:8D15 5A3B7000         | lea rdx,qword ptr ds:[7FF71E9A7CA8]     | 00007FF71E9A7CA8:&"/build\\source\\repos\\volt\\volt-monorepo\\apps\\desktop-interface\\.cargo-home\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tauri-2.9.2\\src\\async_runtime.rs"
00007FF71E2A414E | 48:8D8C24 D0080000       | lea rcx,qword ptr ss:[rsp+8D0]          |
00007FF71E2A4156 | E8 2C500200              | call tauri-app.7FF71E2C9187             |
00007FF71E2A415B | E9 15010000              | jmp tauri-app.7FF71E2A4275              |
00007FF71E2A4160 | 4C:8D05 27982B00         | lea r8,qword ptr ds:[7FF71E55D98E]      | 00007FF71E55D98E:"get_scripts_directory_cmdget_autoexec_directory_cmdget_workspace_directory_cmdopen_folder_in_explorerensure_ignore_folderget_client_settingsupdate_client_settingsget_roblox_path_cmdget_validated_roblox_path_cmdvalidate_roblox_path_cmdroblox_exists_cmdget_roblox_exe_path_cmdget_roblox_version_cmdpick_roblox_directoryvalidate_and_update_roblox_pathget_volt_bin_versionget_volt_bin_version_infoget_file_version_cmddownload_file_from_url_cmdrestore_cached_volt_files_cmdcache_and_uninstall_volt
00007FF71E2A4167 | 41:B9 19000000           | mov r9d,19                              |
00007FF71E2A416D | 48:89F1                  | mov rcx,rsi                             |
00007FF71E2A4170 | 48:89FA                  | mov rdx,rdi                             |
00007FF71E2A4173 | E8 ED04C8FF              | call <tauri-app.sub_7FF71DF24665>       |
00007FF71E2A4178 | 84C0                     | test al,al                              |
00007FF71E2A417A | 0F84 31010000            | je tauri-app.7FF71E2A42B1               |
00007FF71E2A4180 | 48:8DB3 08020000         | lea rsi,qword ptr ds:[rbx+208]          |
00007FF71E2A4187 | 48:8B93 88030000         | mov rdx,qword ptr ds:[rbx+388]          |
00007FF71E2A418E | 4C:8B83 90030000         | mov r8,qword ptr ds:[rbx+390]           |
00007FF71E2A4195 | 48:8B83 A8030000         | mov rax,qword ptr ds:[rbx+3A8]          |
00007FF71E2A419C | 48:898424 40010000       | mov qword ptr ss:[rsp+140],rax          |
00007FF71E2A41A4 | 0F1083 98030000          | movups xmm0,xmmword ptr ds:[rbx+398]    |
00007FF71E2A41AB | 0F298424 30010000        | movaps xmmword ptr ss:[rsp+130],xmm0    |
00007FF71E2A41B3 | 45:31C9                  | xor r9d,r9d                             |
00007FF71E2A41B6 | 48:8D8424 D0080000       | lea rax,qword ptr ss:[rsp+8D0]          |
00007FF71E2A41BE | 83A0 91010000 00         | and dword ptr ds:[rax+191],0            |
00007FF71E2A41C5 | 44:8888 95010000         | mov byte ptr ds:[rax+195],r9b           |
00007FF71E2A41CC | B9 68010000              | mov ecx,168                             |
00007FF71E2A41D1 | 48:89C7                  | mov rdi,rax                             |
00007FF71E2A41D4 | F3:A4                    | rep movsb                               |
00007FF71E2A41D6 | 48:8990 80010000         | mov qword ptr ds:[rax+180],rdx          |
00007FF71E2A41DD | 0F1083 70030000          | movups xmm0,xmmword ptr ds:[rbx+370]    |
00007FF71E2A41E4 | 0F1180 68010000          | movups xmmword ptr ds:[rax+168],xmm0    |
00007FF71E2A41EB | 48:8B8B 80030000         | mov rcx,qword ptr ds:[rbx+380]          |
00007FF71E2A41F2 | 48:8988 78010000         | mov qword ptr ds:[rax+178],rcx          |
00007FF71E2A41F9 | 4C:8980 88010000         | mov qword ptr ds:[rax+188],r8           |
00007FF71E2A4200 | 44:8888 90010000         | mov byte ptr ds:[rax+190],r9b           |
00007FF71E2A4207 | E8 7354E8FF              | call tauri-app.7FF71E12967F             |
00007FF71E2A420C | 833D 8D347A00 02         | cmp dword ptr ds:[7FF71EA476A0],2       |
00007FF71E2A4213 | 0F85 7B010000            | jne tauri-app.7FF71E2A4394              |
00007FF71E2A4219 | 48:8B15 70347A00         | mov rdx,qword ptr ds:[7FF71EA47690]     |
00007FF71E2A4220 | 4C:8B05 71347A00         | mov r8,qword ptr ds:[7FF71EA47698]      |
00007FF71E2A4227 | 48:8DBC24 206A0000       | lea rdi,qword ptr ss:[rsp+6A20]         |
00007FF71E2A422F | 48:89F9                  | mov rcx,rdi                             |
00007FF71E2A4232 | E8 7F3F0B00              | call <tauri-app.sub_7FF71E3581B6>       |
00007FF71E2A4237 | 48:8D15 523A7000         | lea rdx,qword ptr ds:[7FF71E9A7C90]     | 00007FF71E9A7C90:&"/build\\source\\repos\\volt\\volt-monorepo\\apps\\desktop-interface\\.cargo-home\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tauri-2.9.2\\src\\async_runtime.rs"
00007FF71E2A423E | E9 76010000              | jmp tauri-app.7FF71E2A43B9              |
00007FF71E2A4243 | 48:8B15 86347A00         | mov rdx,qword ptr ds:[7FF71EA476D0]     |
00007FF71E2A424A | 4C:8B05 87347A00         | mov r8,qword ptr ds:[7FF71EA476D8]      |
00007FF71E2A4251 | 48:8DBC24 30010000       | lea rdi,qword ptr ss:[rsp+130]          | [rsp+130]:sub_7FF71E191E83+5C
00007FF71E2A4259 | 48:89F9                  | mov rcx,rdi                             |
00007FF71E2A425C | E8 553F0B00              | call <tauri-app.sub_7FF71E3581B6>       |
00007FF71E2A4261 | 48:8D15 403A7000         | lea rdx,qword ptr ds:[7FF71E9A7CA8]     | 00007FF71E9A7CA8:&"/build\\source\\repos\\volt\\volt-monorepo\\apps\\desktop-interface\\.cargo-home\\registry\\src\\index.crates.io-1949cf8c6b5b557f\\tauri-2.9.2\\src\\async_runtime.rs"
00007FF71E2A4268 | 48:8D8C24 D0080000       | lea rcx,qword ptr ss:[rsp+8D0]          |
00007FF71E2A4270 | E8 FD360200              | call <tauri-app.sub_7FF71E2C7972>       |
00007FF71E2A4275 | 48:89C6                  | mov rsi,rax                             |
00007FF71E2A4278 | 48:89F9                  | mov rcx,rdi                             |
00007FF71E2A427B | E8 14B6F1FF              | call <tauri-app.sub_7FF71E1BF894>       |
00007FF71E2A4280 | B9 84000000              | mov ecx,84                              |
00007FF71E2A4285 | B8 CC000000              | mov eax,CC                              |
00007FF71E2A428A | F048:0FB10E              | lock cmpxchg qword ptr ds:[rsi],rcx     |
00007FF71E2A428F | 74 0A                    | je tauri-app.7FF71E2A429B               |
00007FF71E2A4291 | 48:8B46 10               | mov rax,qword ptr ds:[rsi+10]           |
00007FF71E2A4295 | 48:89F1                  | mov rcx,rsi                             |
00007FF71E2A4298 | FF50 20                  | call qword ptr ds:[rax+20]              |
00007FF71E2A429B | B0 01                    | mov al,1                                |
00007FF71E2A429D | 48:81C4 F8990000         | add rsp,99F8                            |
00007FF71E2A42A4 | 5B                       | pop rbx                                 |
00007FF71E2A42A5 | 5D                       | pop rbp                                 |
00007FF71E2A42A6 | 5F                       | pop rdi                                 |
00007FF71E2A42A7 | 5E                       | pop rsi                                 |
00007FF71E2A42A8 | 41:5C                    | pop r12                                 | r12:TranslateMessage
00007FF71E2A42AA | 41:5D                    | pop r13                                 | r13:DispatchMessageW
00007FF71E2A42AC | 41:5E                    | pop r14                                 |
00007FF71E2A42AE | 41:5F                    | pop r15                                 | r15:GetMessageW
00007FF71E2A42B0 | C3                       | ret                                     |
