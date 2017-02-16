
node( 'buildvm-devops' ) {
	input 'Are you certain you want to DELETE the dev-preview-int cluster?'
	sshagent(['dev-preview-int']) {
    		sh 'ssh -o StrictHostKeyChecking=no opsmedic@use-tower1.ops.rhcloud.com delete'
	}
}

