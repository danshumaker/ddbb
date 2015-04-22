# ddbb
Drupal Database Backup

Run ddbb --print for help.

```
Drupal Database Backups:  It pushs and pulls from remote mysql servers as well as does backups of local and remote mysql databases.
 Sample command line : 

ddbb --tbx=sessions,accesslog,cache,cache_form,cache_apachesolr,cache_block,cache_content,cache_filter,cache_menu,cache_page,cache_update,history,search_index,search_dataset,search_total,search_node_links,webform_submitted_data,notifications,notifications_event,notifications_queue,notifications_fields,notifications_sent,watchdog --lmuser=root --lmpass=tacoshop --ldb=testdb --host=localhost --storage=/data/backups/local --lpulldir=/data/backups/remote --rmuser=root --rmpass=tacoshop --rdb=testdb --ruser=dshumaker --rhost=192.168.2.113 --rmhost=192.168.2.74 --rstorage=/home/dshumaker/backups/local --rpushdir=/home/dan/backups/laptop/ --port=3306 


Command line options are:
	--debug           ( off )
	--help            ( off )
	--save            ( off )
	--load            ( off )
	--print           ( off )
	--tbx             ( sessions,accesslog,cache,cache_form,cache_apachesolr,cache_block,cache_content,cache_filter,cache_menu,cache_page,cache_update,history,search_index,search_dataset,search_total,search_node_links,webform_submitted_data,notifications,notifications_event,notifications_queue,notifications_fields,notifications_sent,watchdog )
	--tb              ( off )
	--latest          ( off )
	--fkeys           ( off )
	--gzip            ( off )
	--lmuser          ( root )
	--lmpass          ( tacoshop )
	--ldb             ( testdb )
	--host            ( localhost )
	--storage         ( /data/backups/local )
	--lpulldir        ( /data/backups/remote )
	--rmuser          ( root )
	--rmpass          ( tacoshop )
	--rdb             ( testdb )
	--ruser           ( dshumaker )
	--rhost           ( 192.168.2.113 )
	--rmhost          ( 192.168.2.74 )
	--rstorage        ( /home/dshumaker/backups/local )
	--rpushdir        ( /home/dan/backups/laptop/ )
	--no_ssh          ( off )
	--port            ( 3306 )
	--lb              ( off )
	--rb              ( off )
	--llp             ( off )
	--lll             ( off )
	--push            ( off )
	--pull            ( off )

```
