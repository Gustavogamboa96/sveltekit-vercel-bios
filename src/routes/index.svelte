<script>
    import {twit} from 'Twit'

    
const client = new Twit({
    consumer_key: 'BYFev5CvRdyx7EgOQpLKEwTLG',
    consumer_secret: 'dkDkC4NSRTTAjcRJaGeD9hlXfTJOPFBiAIhvEdaSTJZKTtGnJp',
    access_token: '51788921-CMYMxgZ4TvOP7OjXTqC8GsjULjn0hfjzCsifAkHCj',
    access_token_secret: 'pwImFpNUQr86ar85bX2azpnvLgwWENqYkmMDQ2iEcJGvs',
    //timeout_ms: 60*1000,
})

client.get('users/show', {screen_name: 'cangrejozurdo'}, function(err, data, response){
        res.send(data.description);
        console.log(data.description)
})
</script>
