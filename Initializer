    public class Initializer : IModuleBinder
    {
        private List<HtmlGenericControl> genericControl = null;

        public List<HtmlGenericControl> ControlDefinitionMetaTags()
        {
            genericControl = new List<HtmlGenericControl>();

            try
            {
                HtmlGenericControl metaTagCharSet = new HtmlGenericControl("meta");
                metaTagCharSet.Attributes.Add("charset", "utf-8");
                genericControl.Add(metaTagCharSet);

                HtmlGenericControl metaTagCompatibility = new HtmlGenericControl("meta");
                metaTagCompatibility.Attributes.Add("http-equiv", "X-UA-Compatible");
                genericControl.Add(metaTagCompatibility);

                HtmlGenericControl metaTagEdge = new HtmlGenericControl("meta");
                metaTagEdge.Attributes.Add("content", "IE=edge");
                genericControl.Add(metaTagEdge);

                HtmlGenericControl metaTagViewPort = new HtmlGenericControl("meta");
                metaTagViewPort.Attributes.Add("name", "viewport");
                metaTagViewPort.Attributes.Add("content", "width=device-width,initial-scale=1");
                genericControl.Add(metaTagViewPort);

                HtmlGenericControl metaTagAuthors = new HtmlGenericControl("meta");
                metaTagAuthors.Attributes.Add("name", "author");
                metaTagAuthors.Attributes.Add("content", "Mahesh");
                genericControl.Add(metaTagAuthors);

                return genericControl;
            }
            catch (Exception ex)
            {
                throw ex;
            }
        }
    }
