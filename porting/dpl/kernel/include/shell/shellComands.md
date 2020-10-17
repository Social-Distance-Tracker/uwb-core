
# Shell commands

##  console: 

´´´compat> ´´´

# Commands 
## help
Displays: 

´´´
928903 help
928903 stat                          
928903 config                        
928903 dw1000                        dw1000 dbg
928903 tasks                         show os tasks
928904 mpool                         show system mpool
928904 date                          show system date
928904 reset                         reset system
928905 lsdev                         list OS devices
928906 compat> 

´´´

## stat
options 
´´´
1189295 	stat
1189295 	ble_l2cap
1189295 	ble_att
1189295 	ble_gap
1189295 	ble_gattc
1189295 	ble_gatts
1189295 	ble_hs
1189295 	ble_ll_conn
1189295 	ble_phy
1189295 	ble_ll
1189295 	mac
´´´

### stat stat

### stat ble_l2cap

### stat ble_att

### stat ble_gap

### stat ble_gattc

### stat ble_gatts

### stat ble_hs

### stat ble_ll_conn

### stat ble_phy

### stat ble_ll

### stat mac

## config   
Get and set configs on the fly

### config commit 
make current changes active

### config save                   
Save to flash so this new change is used even after reset

### config dump
Outputs current configuration
Ex. 
´´´
229652 lstnr/acc_samples = 0
229652 lstnr/verbose = 0x0
229652 uwb/channel = 5
229652 uwb/prf = 64
229652 uwb/datarate = 6m8
229652 uwb/rx_paclen = 8
229652 uwb/rx_pream_cidx = 9
229652 uwb/rx_sfdtype = 1
229652 uwb/rx_sfd_to = -1
229652 uwb/rx_phrmode = e
229653 uwb/rx_diag_en = 0x1
229653 uwb/tx_pream_cidx = 9
229654 uwb/tx_pream_len = 128
229654 uwb/txrf_power_coarse = 15
229654 uwb/txrf_power_fine = 22
229655 uwb/rx_antdly = 0x4050
229655 uwb/tx_antdly = 0x4050
229655 uwb/rx_ant_separation = 0.0205
229656 uwb/ext_clkdly = 0
229656 uwb/role = 0x0000
229656 uwb/frame_filter = 0x0000
229657 uwb/xtal_trim = 0xff
229657 split/status = 0
229657 ble_hs/our_sec = 
229658 ble_hs/peer_sec = 
229658 ble_hs/cccd = 
229658 reboot/reboot_cnt = 
229659 reboot/written = 
´´´


                     
## dw1000                        
Summary:
dw1000 dbg
Usage:
dw1000 debug
Parameters:
dump                          [inst] dump all registers
cw                            <inst> tx CW on current channel
da                            <inst> <addr> [length], dump area
rd                            <inst> <addr> <subaddr> <length>, read register
wr                            <inst> <addr> <subaddr> <value> <length>, write value to register


## tasks                         
Summary:
show os tasks
Parameters: 
task name

## mpool                         
show system mpool
Parameters:
mpool name

## date                          
show system date

## reset                         
reset system

## lsdev                         
list OS devices

