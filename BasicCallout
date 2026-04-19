public with sharing class BasicCallout {
    public BasicCallout() {

    }
    public static void makeCallout() {
        HttpRequest req = new HttpRequest();
        req.setEndpoint('https://global-warming.org/api/temperature-api');
        req.setMethod('GET');
        Http http = new Http();
        HttpResponse res = http.send(req);

        if(res.getStatusCode() == 200) {
            // String resp = JSON.serializePretty(res.getBody());
            System.debug('Response: ' + res.getBody());
        } else {
            System.debug('Error: ' + res.getStatusCode());
        }
    }
}
